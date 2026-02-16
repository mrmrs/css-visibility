# css-visibility

Functional CSS for visibility

## Filesize

| File | Size |
|------|------|
| `dist/visibility.css` | 1755 bytes |
| `dist/visibility.min.css` | 1343 bytes (260 Gzipped) |

## Install

```sh
npm install css-visibility
```

## Usage

### Import

```css
@import "css-visibility";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-visibility/dist/visibility.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-visibility/dist/visibility.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.visible` | `visibility: visible;` |
| `.hidden` | `visibility: hidden;` |
| `.visibility-collapse` | `visibility: collapse;` |
| `.backface-visible` | `backface-visibility: visible;` |
| `.backface-hidden` | `backface-visibility: hidden;` |
| `.clip` | `clip: rect(1px 1px 1px 1px);   clip: rect(1px, 1px, 1px, 1px);   _position: absolute !important;   position: fixed !important;` |
| `.visible-s` | `visibility: visible;` |
| `.hidden-s` | `visibility: hidden;` |
| `.visibility-collapse-s` | `visibility: collapse;` |
| `.backface-visible-s` | `backface-visibility: visible;` |
| `.backface-hidden-s` | `backface-visibility: hidden;` |
| `.clip-s` | `clip: rect(1px 1px 1px 1px);     clip: rect(1px, 1px, 1px, 1px);     _position: absolute !important;     position: fixed !important;` |
| `.visible-m` | `visibility: visible;` |
| `.hidden-m` | `visibility: hidden;` |
| `.visibility-collapse-m` | `visibility: collapse;` |
| `.backface-visible-m` | `backface-visibility: visible;` |
| `.backface-hidden-m` | `backface-visibility: hidden;` |
| `.clip-m` | `clip: rect(1px 1px 1px 1px);     clip: rect(1px, 1px, 1px, 1px);     _position: absolute !important;     position: fixed !important;` |
| `.visible-l` | `visibility: visible;` |
| `.hidden-l` | `visibility: hidden;` |
| `.visibility-collapse-l` | `visibility: collapse;` |
| `.backface-visible-l` | `backface-visibility: visible;` |
| `.backface-hidden-l` | `backface-visibility: hidden;` |
| `.clip-l` | `clip: rect(1px 1px 1px 1px);     clip: rect(1px, 1px, 1px, 1px);     _position: absolute !important;     position: fixed !important;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.visible-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/visibility.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/visibility.css` — formatted
- `dist/visibility.min.css` — minified

## License

MIT
