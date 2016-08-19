# css-z-index 0.0.7

Css module of single purpose classes for z index

#### Stats

284 | 44 | 44
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-z-index
```

#### With Git

```
git clone https://github.com/tachyons-css/css-z-index
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-z-index";
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
<link rel="stylesheet" href="path/to/module/css/css-z-index">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   Z INDEX
*/
.z-1 { z-index: 1; }
.z-100 { z-index: 100; }
.z-200 { z-index: 200; }
.z-300 { z-index: 300; }
.z-400 { z-index: 400; }
.z-500 { z-index: 500; }
.z-600 { z-index: 600; }
.z-700 { z-index: 700; }
.z-800 { z-index: 800; }
.z-900 { z-index: 900; }
.z-999 { z-index: 999; }
@media screen and (min-width: 48em) {
 .z-1-ns { z-index: 1; }
 .z-100-ns { z-index: 100; }
 .z-200-ns { z-index: 200; }
 .z-300-ns { z-index: 300; }
 .z-400-ns { z-index: 400; }
 .z-500-ns { z-index: 500; }
 .z-600-ns { z-index: 600; }
 .z-700-ns { z-index: 700; }
 .z-800-ns { z-index: 800; }
 .z-900-ns { z-index: 900; }
 .z-999-ns { z-index: 999; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .z-1-m { z-index: 1; }
 .z-100-m { z-index: 100; }
 .z-200-m { z-index: 200; }
 .z-300-m { z-index: 300; }
 .z-400-m { z-index: 400; }
 .z-500-m { z-index: 500; }
 .z-600-m { z-index: 600; }
 .z-700-m { z-index: 700; }
 .z-800-m { z-index: 800; }
 .z-900-m { z-index: 900; }
 .z-999-m { z-index: 999; }
}
@media screen and (min-width: 64em) {
 .z-1-l { z-index: 1; }
 .z-100-l { z-index: 100; }
 .z-200-l { z-index: 200; }
 .z-300-l { z-index: 300; }
 .z-400-l { z-index: 400; }
 .z-500-l { z-index: 500; }
 .z-600-l { z-index: 600; }
 .z-700-l { z-index: 700; }
 .z-800-l { z-index: 800; }
 .z-900-l { z-index: 900; }
 .z-999-l { z-index: 999; }
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
