# CSS VISIBILITY

  Mobile-first classes for css-visibility.
  Set the desired css-visibility on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
```
npm install --save-dev css-visibility
```
or download the css on github and include in your project.

## File Size


## The Code
```
.vis          { visibility: visible; }
.vis-hidden   { visibility: hidden; }
.vis-collapse { visibility: collapse; }

.vis-bf-vis {   backface-visibility: visible; }
.vis-bf-hid {   backface-visibility: hidden; }

/*
    Text that is hidden but accessible
    Ref: http://snook.ca/archives/html_and_css/hiding-content-for-accessibility
*/

.clip {
  position: fixed !important;
  _position: absolute !important;
  clip: rect(1px 1px 1px 1px); /* IE6, IE7 */
  clip: rect(1px, 1px, 1px, 1px);
}

@media screen and (min-width: 48em) {
  .vis-ns          { visibility: visible; }
  .vis-hidden-ns   { visibility: hidden; }
  .vis-collapse-ns { visibility: collapse; }
  .vis-bf-vis-ns {   backface-visibility: visible; }
  .vis-bf-hid-ns {   backface-visibility: hidden; }
  .clip-ns {
    position: fixed !important;
    _position: absolute !important;
    clip: rect(1px 1px 1px 1px); /* IE6, IE7 */
    clip: rect(1px, 1px, 1px, 1px);
  }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .vis-m          { visibility: visible; }
  .vis-hidden-m   { visibility: hidden; }
  .vis-collapse-m { visibility: collapse; }
  .vis-bf-vis-m { backface-visibility: visible; }
  .vis-bf-hid-m { backface-visibility: hidden; }
  .clip-m {
    position: fixed !important;
    _position: absolute !important;
    clip: rect(1px 1px 1px 1px); /* IE6, IE7 */
    clip: rect(1px, 1px, 1px, 1px);
  }
}

@media screen and (min-width: 64em)  {
  .vis-l          { visibility: visible; }
  .vis-hidden-l   { visibility: hidden; }
  .vis-collapse-l { visibility: collapse; }
  .vis-bf-vis-l { backface-visibility: visible; }
  .vis-bf-hid-l { backface-visibility: hidden; }
  .clip-l {
    position: fixed !important;
    _position: absolute !important;
    clip: rect(1px 1px 1px 1px); /* IE6, IE7 */
    clip: rect(1px, 1px, 1px, 1px);
  }
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

