# css-z-index

Single purpose CSS classes for z-index.

## Install

```sh
npm install css-z-index
```

## Usage

### Import

```css
@import "css-z-index";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-z-index/dist/css-z-index.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-z-index/dist/css-z-index.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.z1`   | `z-index: 1`            |
| `.z2`   | `z-index: 100`          |
| `.z3`   | `z-index: 200`          |
| `.z4`   | `z-index: 300`          |
| `.z5`   | `z-index: 400`          |
| `.z6`   | `z-index: 500`          |
| `.z7`   | `z-index: 600`          |
| `.z8`   | `z-index: 700`          |
| `.z9`   | `z-index: 800`          |
| `.z10`  | `z-index: 900`          |
| `.z11`  | `z-index: 2147483647`   |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.z5-m` applies `z-index: 400` at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/css-z-index.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/css-z-index.css` — formatted
- `dist/css-z-index.min.css` — minified

## License

MIT
