# 3d-print-letterpress
========
Converts OpenType and TrueType (.otf and .ttf) files into 3D printable (.stl) models of letterpress type for a specified point size and glyph.


Installation
------------

3d-print-letterpress requires [node.js](http://nodejs.org).

Install via [npm](https://www.npmjs.org)
```
$ npm install git+ssh://git@github.com:jonathanzong/3d-print-letterpress.git -g
```

Usage Example
-------------
3d-print-letterpress type-file [point-size [glyph]]
```
$ 3d-print-letterpress Gotham-Book.otf 16 H
output written to Gotham-BookH16pt.stl
```

Dependencies
-----------
3d-print-letterpress uses

- [opentype](https://github.com/nodebox/opentype.js) -- parser for OpenType and TrueType formats
- [JSModeler](https://github.com/kovacsv/JSModeler) -- 3D modeling library modifed here to work in Node.js (removed references to the DOM)
- [point-at-length](https://github.com/substack/point-at-length) -- SVG utility to perform path calculations


License
-----------
MIT
