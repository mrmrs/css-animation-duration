# css-animation-duration 1.0.8

Css module of single purpose classes for animation duration

#### Stats

411 | 52 | 104
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-animation-duration
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/css-animation-duration
```

ssh:
```
git clone git@github.com:tachyons-css/css-animation-duration.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-animation-duration";
```

Then process the css using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons path/to/css-file.css > dist/t.css
```

#### Using the css

##### CDN
The easiest and most simple way to use the css is to use the cdn hosted version. Include it in the head of your html with:

```
<link rel="stylesheet" href="http://unpkg.com/css-animation-duration@1.0.8/css/css-animation-duration.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-animation-duration">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/*
   ANIMATION DURATION
*/
.a-dur0 { -webkit-animation-duration: 0; animation-duration: 0; }
.a-dur1 { -webkit-animation-duration: .1s; animation-duration: .1s; }
.a-dur2 { -webkit-animation-duration: .2s; animation-duration: .2s; }
.a-dur3 { -webkit-animation-duration: .4s; animation-duration: .4s; }
.a-dur4 { -webkit-animation-duration: .5s; animation-duration: .5s; }
.a-dur5 { -webkit-animation-duration: .7s; animation-duration: .7s; }
.a-dur6 { -webkit-animation-duration: 1s; animation-duration: 1s; }
.a-dur7 { -webkit-animation-duration: 1.5s; animation-duration: 1.5s; }
.a-dur8 { -webkit-animation-duration: 2s; animation-duration: 2s; }
.a-dur9 { -webkit-animation-duration: 2.5s; animation-duration: 2.5s; }
.a-dur10 { -webkit-animation-duration: 4s; animation-duration: 4s; }
.a-dur11 { -webkit-animation-duration: 8s; animation-duration: 8s; }
.a-dur12 { -webkit-animation-duration: 12s; animation-duration: 12s; }
@media screen and (min-width: 48em) {
 .a-dur0-ns { -webkit-animation-duration: 0; animation-duration: 0; }
 .a-dur1-ns { -webkit-animation-duration: .1s; animation-duration: .1s; }
 .a-dur2-ns { -webkit-animation-duration: .2s; animation-duration: .2s; }
 .a-dur3-ns { -webkit-animation-duration: .4s; animation-duration: .4s; }
 .a-dur4-ns { -webkit-animation-duration: .5s; animation-duration: .5s; }
 .a-dur5-ns { -webkit-animation-duration: .7s; animation-duration: .7s; }
 .a-dur6-ns { -webkit-animation-duration: 1s; animation-duration: 1s; }
 .a-dur7-ns { -webkit-animation-duration: 1.5s; animation-duration: 1.5s; }
 .a-dur8-ns { -webkit-animation-duration: 2s; animation-duration: 2s; }
 .a-dur9-ns { -webkit-animation-duration: 2.5s; animation-duration: 2.5s; }
 .a-dur10-ns { -webkit-animation-duration: 4s; animation-duration: 4s; }
 .a-dur11-ns { -webkit-animation-duration: 8s; animation-duration: 8s; }
 .a-dur12-ns { -webkit-animation-duration: 12s; animation-duration: 12s; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .a-dur0-m { -webkit-animation-duration: 0; animation-duration: 0; }
 .a-dur1-m { -webkit-animation-duration: .1s; animation-duration: .1s; }
 .a-dur2-m { -webkit-animation-duration: .2s; animation-duration: .2s; }
 .a-dur3-m { -webkit-animation-duration: .4s; animation-duration: .4s; }
 .a-dur4-m { -webkit-animation-duration: .5s; animation-duration: .5s; }
 .a-dur5-m { -webkit-animation-duration: .7s; animation-duration: .7s; }
 .a-dur6-m { -webkit-animation-duration: 1s; animation-duration: 1s; }
 .a-dur7-m { -webkit-animation-duration: 1.5s; animation-duration: 1.5s; }
 .a-dur8-m { -webkit-animation-duration: 2s; animation-duration: 2s; }
 .a-dur9-m { -webkit-animation-duration: 2.5s; animation-duration: 2.5s; }
 .a-dur10-m { -webkit-animation-duration: 4s; animation-duration: 4s; }
 .a-dur11-m { -webkit-animation-duration: 8s; animation-duration: 8s; }
 .a-dur12-m { -webkit-animation-duration: 12s; animation-duration: 12s; }
}
@media screen and (min-width: 64em) {
 .a-dur0-l { -webkit-animation-duration: 0; animation-duration: 0; }
 .a-dur1-l { -webkit-animation-duration: .1s; animation-duration: .1s; }
 .a-dur2-l { -webkit-animation-duration: .2s; animation-duration: .2s; }
 .a-dur3-l { -webkit-animation-duration: .4s; animation-duration: .4s; }
 .a-dur4-l { -webkit-animation-duration: .5s; animation-duration: .5s; }
 .a-dur5-l { -webkit-animation-duration: .7s; animation-duration: .7s; }
 .a-dur6-l { -webkit-animation-duration: 1s; animation-duration: 1s; }
 .a-dur7-l { -webkit-animation-duration: 1.5s; animation-duration: 1.5s; }
 .a-dur8-l { -webkit-animation-duration: 2s; animation-duration: 2s; }
 .a-dur9-l { -webkit-animation-duration: 2.5s; animation-duration: 2.5s; }
 .a-dur10-l { -webkit-animation-duration: 4s; animation-duration: 4s; }
 .a-dur11-l { -webkit-animation-duration: 8s; animation-duration: 8s; }
 .a-dur12-l { -webkit-animation-duration: 12s; animation-duration: 12s; }
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [mrmrs](http://mrmrs.io)
* [johno](http://johnotander.com)

## License

ISC

