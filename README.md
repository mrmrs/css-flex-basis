# css-flex-basis

Functional CSS for flex-basis

## Filesize

| File | Size |
|------|------|
| `dist/flex-basis.css` | 329 bytes |
| `dist/flex-basis.min.css` | 261 bytes (103 Gzipped) |

## Install

```sh
npm install css-flex-basis
```

## Usage

### Import

```css
@import "css-flex-basis";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-flex-basis/dist/flex-basis.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-flex-basis/dist/flex-basis.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.flex-basis-inherit` | `flex-basis: inherit;` |
| `.flex-basis-inherit-s` | `flex-basis: inherit;` |
| `.flex-basis-inherit-m` | `flex-basis: inherit;` |
| `.flex-basis-inherit-l` | `flex-basis: inherit;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.flex-basis-inherit-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/flex-basis.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/flex-basis.css` — formatted
- `dist/flex-basis.min.css` — minified

## License

MIT
