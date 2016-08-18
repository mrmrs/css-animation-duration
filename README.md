# css-animation-duration 0.0.7

Css module of single purpose classes for animation duration

#### Stats

344 | 52 | 52
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-animation-duration
```

#### With Git

```
git clone https://github.com/tachyons-css/css-animation-duration
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-animation-duration";
```

Then process the CSS using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons-cli path/to/css-file.css > dist/t.css
```

#### Using the CSS

The built CSS is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-animation-duration">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   ANIMATION DURATION
*/
.a-dur0 { animation-duration: 0; }
.a-dur1 { animation-duration: .1s; }
.a-dur2 { animation-duration: .2s; }
.a-dur3 { animation-duration: .4s; }
.a-dur4 { animation-duration: .5s; }
.a-dur5 { animation-duration: .7s; }
.a-dur6 { animation-duration: 1s; }
.a-dur7 { animation-duration: 1.5s; }
.a-dur8 { animation-duration: 2s; }
.a-dur9 { animation-duration: 2.5s; }
.a-dur10 { animation-duration: 4s; }
.a-dur11 { animation-duration: 8s; }
.a-dur12 { animation-duration: 12s; }
@media screen and (min-width: 48em) {
 .a-dur0-ns { animation-duration: 0; }
 .a-dur1-ns { animation-duration: .1s; }
 .a-dur2-ns { animation-duration: .2s; }
 .a-dur3-ns { animation-duration: .4s; }
 .a-dur4-ns { animation-duration: .5s; }
 .a-dur5-ns { animation-duration: .7s; }
 .a-dur6-ns { animation-duration: 1s; }
 .a-dur7-ns { animation-duration: 1.5s; }
 .a-dur8-ns { animation-duration: 2s; }
 .a-dur9-ns { animation-duration: 2.5s; }
 .a-dur10-ns { animation-duration: 4s; }
 .a-dur11-ns { animation-duration: 8s; }
 .a-dur12-ns { animation-duration: 12s; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .a-dur0-m { animation-duration: 0; }
 .a-dur1-m { animation-duration: .1s; }
 .a-dur2-m { animation-duration: .2s; }
 .a-dur3-m { animation-duration: .4s; }
 .a-dur4-m { animation-duration: .5s; }
 .a-dur5-m { animation-duration: .7s; }
 .a-dur6-m { animation-duration: 1s; }
 .a-dur7-m { animation-duration: 1.5s; }
 .a-dur8-m { animation-duration: 2s; }
 .a-dur9-m { animation-duration: 2.5s; }
 .a-dur10-m { animation-duration: 4s; }
 .a-dur11-m { animation-duration: 8s; }
 .a-dur12-m { animation-duration: 12s; }
}
@media screen and (min-width: 64em) {
 .a-dur0-l { animation-duration: 0; }
 .a-dur1-l { animation-duration: .1s; }
 .a-dur2-l { animation-duration: .2s; }
 .a-dur3-l { animation-duration: .4s; }
 .a-dur4-l { animation-duration: .5s; }
 .a-dur5-l { animation-duration: .7s; }
 .a-dur6-l { animation-duration: 1s; }
 .a-dur7-l { animation-duration: 1.5s; }
 .a-dur8-l { animation-duration: 2s; }
 .a-dur9-l { animation-duration: 2.5s; }
 .a-dur10-l { animation-duration: 4s; }
 .a-dur11-l { animation-duration: 8s; }
 .a-dur12-l { animation-duration: 12s; }
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
