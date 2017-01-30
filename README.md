pixi-sdf-text
=============

Signed distance fields text implementation for PixiJS
-----------------------------------------------------

<a href="https://www.mapbox.com/blog/text-signed-distance-fields/">SDF is the most efficient way to draw text in WebGL</a>.
        It uses <a href="http://pixelscommander.com/polygon/pixi-sdf-text/assets/OpenSans-Regular.png">special kind of raster atlases</a> and GLSL shader to <a href="http://wdobbie.com/pdf/">draw vector scalable text in a very performant way</a> on GPU.</p>

[Demo](http://pixelscommander.com/polygon/pixi-sdf-text/demo/)

Installation
------------

`npm i pixi-sdf-text --save`

Usage
-----

```javascript
var style = {
	fontSize: 24,
	color: 0x39FF14,
	metrics: window.fontMetrics,
	texture: resources.font.texture
};
window.text = new PIXI.sdf.Text('Abc', style);
```

Bugs
----
Feel free to submit issues to [GitHub tracker](https://github.com/PixelsCommander/pixi-sdf-text/issues)

License
-------
MIT: [http://mit-license.org/](http://mit-license.org/)

Copyright 2017 Denis Radin aka [PixelsCommander](http://pixelscommander.com)