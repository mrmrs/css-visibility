# css-visibility 0.0.6

Css module of single purpose classes for visibility

#### Stats

405 | 24 | 36
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-visibility
```

#### With Git

```
git clone https://github.com/tachyons-css/css-visibility
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-visibility";
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
<link rel="stylesheet" href="path/to/module/css/css-visibility">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   VISIBILITY
*/
.vis { visibility: visible; }
.vis-hidden { visibility: hidden; }
.vis-collapse { visibility: collapse; }
.vis-bf-vis { backface-visibility: visible; }
.vis-bf-hid { backface-visibility: hidden; }
/*
    Text that is hidden but accessible
    Ref: http://snook.ca/archives/html_and_css/hiding-content-for-accessibility
*/
.clip { position: fixed !important; _position: absolute !important; clip: rect( 1px 1px 1px 1px ); /* IE6, IE7 */ clip: rect( 1px, 1px, 1px, 1px ); }
@media screen and (min-width: 48em) {
 .vis-ns { visibility: visible; }
 .vis-hidden-ns { visibility: hidden; }
 .vis-collapse-ns { visibility: collapse; }
 .vis-bf-vis-ns { backface-visibility: visible; }
 .vis-bf-hid-ns { backface-visibility: hidden; }
 .clip-ns { position: fixed !important; position: absolute !important; clip: rect( 1px 1px 1px 1px ); /* IE6, IE7 */ clip: rect( 1px, 1px, 1px, 1px ); }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .vis-m { visibility: visible; }
 .vis-hidden-m { visibility: hidden; }
 .vis-collapse-m { visibility: collapse; }
 .vis-bf-vis-m { backface-visibility: visible; }
 .vis-bf-hid-m { backface-visibility: hidden; }
 .clip-m { position: fixed !important; position: absolute !important; clip: rect( 1px 1px 1px 1px ); /* IE6, IE7 */ clip: rect( 1px, 1px, 1px, 1px ); }
}
@media screen and (min-width: 64em) {
 .vis-l { visibility: visible; }
 .vis-hidden-l { visibility: hidden; }
 .vis-collapse-l { visibility: collapse; }
 .vis-bf-vis-l { backface-visibility: visible; }
 .vis-bf-hid-l { backface-visibility: hidden; }
 .clip-l { position: fixed !important; position: absolute !important; clip: rect( 1px 1px 1px 1px ); /* IE6, IE7 */ clip: rect( 1px, 1px, 1px, 1px ); }
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
