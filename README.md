# CSS Z INDEX

  Mobile-first classes for css-z-index.
  Set the desired css-z-index on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
```
npm install --save-dev css-z-index
```
or download the css on github and include in your project.

## File Size


## The Code
```
.z-1    { z-index: 1; }
.z-100  { z-index: 100; }
.z-200  { z-index: 200; }
.z-300  { z-index: 300; }
.z-400  { z-index: 400; }
.z-500  { z-index: 500; }
.z-600  { z-index: 600; }
.z-700  { z-index: 700; }
.z-800  { z-index: 800; }
.z-900  { z-index: 900; }
.z-999  { z-index: 999; }

@media screen and (min-width: 48em) {
  .z-1-ns    { z-index: 1; }
  .z-100-ns  { z-index: 100; }
  .z-200-ns  { z-index: 200; }
  .z-300-ns  { z-index: 300; }
  .z-400-ns  { z-index: 400; }
  .z-500-ns  { z-index: 500; }
  .z-600-ns  { z-index: 600; }
  .z-700-ns  { z-index: 700; }
  .z-800-ns  { z-index: 800; }
  .z-900-ns  { z-index: 900; }
  .z-999-ns  { z-index: 999; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .z-1-m    { z-index: 1; }
  .z-100-m  { z-index: 100; }
  .z-200-m  { z-index: 200; }
  .z-300-m  { z-index: 300; }
  .z-400-m  { z-index: 400; }
  .z-500-m  { z-index: 500; }
  .z-600-m  { z-index: 600; }
  .z-700-m  { z-index: 700; }
  .z-800-m  { z-index: 800; }
  .z-900-m  { z-index: 900; }
  .z-999-m  { z-index: 999; }
}

@media screen and (min-width: 64em)  {
  .z-1-l    { z-index: 1; }
  .z-100-l  { z-index: 100; }
  .z-200-l  { z-index: 200; }
  .z-300-l  { z-index: 300; }
  .z-400-l  { z-index: 400; }
  .z-500-l  { z-index: 500; }
  .z-600-l  { z-index: 600; }
  .z-700-l  { z-index: 700; }
  .z-800-l  { z-index: 800; }
  .z-900-l  { z-index: 900; }
  .z-999-l  { z-index: 999; }
}

```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2014 @mrmrs

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

