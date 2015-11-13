# Grits
Simple inline-block grid library. Inline-block grids are great for flexbox fallbacks
or to use them as the CSS behind your grid system.

## How to Use Grits

### Install with Bower
1. Run `bower install grits`
2. Import grits at the beginning of your stylesheet

  ```scss
  @import 'path/to/bower/grits/grits';
  ```

**Note:** *The path for Grits might be different in your project*

### Manuel Install
1. Download Grits zip and include `grits` folder into your project
2. Import Grits at the beginning of your stylesheet

  ```scss
  @import 'path/to/grits/grits';
  ```

## Inline-block Hack
There have been many ways to work around ```display: inline-block;``` white-space.
Grits sets the row to ```font-size: 0```. This removes all the white-space between
elements. Each column mixin resets the font to ```font-size: 1rem```.

### Why 1rem
Much like ```em```, ```rem``` is also a relative CSS unit. However ```rem``` units
do not have any inheritance and only references the root element, usually the
```html``` element.

## License
The MIT License (MIT)

Copyright (c) 2014 Azin Asili

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
