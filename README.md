# CSS ANIMATION DURATION

  Mobile-first classes for css-animation-duration.
  Set the desired css-animation-duration on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
Grab the css partial from github and include it in your project or alternatively
you can install it via npm:
```
npm install --save-dev css-animation-duration
```
View on [npm](https://www.npmjs.org/package/css-animation-duration)


## File Size

2.3K animation-duration.css
1.8K animation-duration.min.css
296B minified and gzipped

## The Code
```
  .a-dur0  { animation-duration: 0; }
  .a-dur1  { animation-duration: .1s; }
  .a-dur2  { animation-duration: .2s; }
  .a-dur3  { animation-duration: .4s; }
  .a-dur4  { animation-duration: .5s; }
  .a-dur5  { animation-duration: .7s; }
  .a-dur6  { animation-duration: 1s;  }
  .a-dur7  { animation-duration: 1.5s; }
  .a-dur8  { animation-duration: 2s; }
  .a-dur9  { animation-duration: 2.5s; }
  .a-dur10 { animation-duration: 4s;  }
  .a-dur11 { animation-duration: 8s;  }
  .a-dur12 { animation-duration: 12s;  }

@media screen and (min-width: 48em) {
  .a-dur0-ns   { animation-duration: 0; }
  .a-dur1-ns   { animation-duration: .1s; }
  .a-dur2-ns   { animation-duration: .2s; }
  .a-dur3-ns   { animation-duration: .4s; }
  .a-dur4-ns   { animation-duration: .5s; }
  .a-dur5-ns   { animation-duration: .7s; }
  .a-dur6-ns   { animation-duration: 1s;  }
  .a-dur7-ns   { animation-duration: 1.5s; }
  .a-dur8-ns   { animation-duration: 2s; }
  .a-dur9-ns   { animation-duration: 2.5s; }
  .a-dur10-ns  { animation-duration: 4s;  }
  .a-dur11-ns  { animation-duration: 8s;  }
  .a-dur12-ns  { animation-duration: 12s;  }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .a-dur0-m   { animation-duration: 0; }
  .a-dur1-m   { animation-duration: .1s; }
  .a-dur2-m   { animation-duration: .2s; }
  .a-dur3-m   { animation-duration: .4s; }
  .a-dur4-m   { animation-duration: .5s; }
  .a-dur5-m   { animation-duration: .7s; }
  .a-dur6-m   { animation-duration: 1s;  }
  .a-dur7-m   { animation-duration: 1.5s; }
  .a-dur8-m   { animation-duration: 2s; }
  .a-dur9-m   { animation-duration: 2.5s; }
  .a-dur10-m  { animation-duration: 4s;  }
  .a-dur11-m  { animation-duration: 8s;  }
  .a-dur12-m  { animation-duration: 12s;  }
}

@media screen and (min-width: 64em)  {
  .a-dur0-l   { animation-duration: 0; }
  .a-dur1-l   { animation-duration: .1s; }
  .a-dur2-l   { animation-duration: .2s; }
  .a-dur3-l   { animation-duration: .4s; }
  .a-dur4-l   { animation-duration: .5s; }
  .a-dur5-l   { animation-duration: .7s; }
  .a-dur6-l   { animation-duration: 1s;  }
  .a-dur7-l   { animation-duration: 1.5s; }
  .a-dur8-l   { animation-duration: 2s; }
  .a-dur9-l   { animation-duration: 2.5s; }
  .a-dur10-l  { animation-duration: 4s;  }
  .a-dur11-l  { animation-duration: 8s;  }
  .a-dur12-l  { animation-duration: 12s;  }
}
```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2015 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

