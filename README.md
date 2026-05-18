# css-visibility

Functional CSS for visibility

## Filesize

| File | Size |
|------|------|
| `dist/visibility.css` | 1683 bytes |
| `dist/visibility.min.css` | 1271 bytes (257 Gzipped) |

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
| `.vis` | `visibility: visible;` |
| `.vis-hidden` | `visibility: hidden;` |
| `.vis-collapse` | `visibility: collapse;` |
| `.vis-bf-vis` | `backface-visibility: visible;` |
| `.vis-bf-hid` | `backface-visibility: hidden;` |
| `.clip` | `clip: rect(1px 1px 1px 1px);   clip: rect(1px, 1px, 1px, 1px);   _position: absolute !important;   position: fixed !important;` |
| `.vis-s` | `visibility: visible;` |
| `.vis-hidden-s` | `visibility: hidden;` |
| `.vis-collapse-s` | `visibility: collapse;` |
| `.vis-bf-vis-s` | `backface-visibility: visible;` |
| `.vis-bf-hid-s` | `backface-visibility: hidden;` |
| `.clip-s` | `clip: rect(1px 1px 1px 1px);     clip: rect(1px, 1px, 1px, 1px);     _position: absolute !important;     position: fixed !important;` |
| `.vis-m` | `visibility: visible;` |
| `.vis-hidden-m` | `visibility: hidden;` |
| `.vis-collapse-m` | `visibility: collapse;` |
| `.vis-bf-vis-m` | `backface-visibility: visible;` |
| `.vis-bf-hid-m` | `backface-visibility: hidden;` |
| `.clip-m` | `clip: rect(1px 1px 1px 1px);     clip: rect(1px, 1px, 1px, 1px);     _position: absolute !important;     position: fixed !important;` |
| `.vis-l` | `visibility: visible;` |
| `.vis-hidden-l` | `visibility: hidden;` |
| `.vis-collapse-l` | `visibility: collapse;` |
| `.vis-bf-vis-l` | `backface-visibility: visible;` |
| `.vis-bf-hid-l` | `backface-visibility: hidden;` |
| `.clip-l` | `clip: rect(1px 1px 1px 1px);     clip: rect(1px, 1px, 1px, 1px);     _position: absolute !important;     position: fixed !important;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.vis-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/visibility.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/visibility.css` — formatted
- `dist/visibility.min.css` — minified

## License

MIT
