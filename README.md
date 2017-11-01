<p align="center"> 
  <img src="https://avatars0.githubusercontent.com/u/33233302?s=400&u=5fce4d3bd8100ad7ea284d12b948e5f09444dd55&v=4">
</p>
Integrated-2D is a Javascript framework, for rendering 2D graphics on SVG and Canvas contexts. It's simple syntax and semantics lets you combine the power of Vector graphics and Bitmap to achieve complex visualisations easily.

For efficient rendering I2D creates elements called mini Virtual Doms, virtual representation of rendered graphics.

## Installing

Download source code from below links

* [i2D.js](https://raw.githubusercontent.com/I2djs/I2D/master/dist/i2d.js) 
* [i2D.min.js](https://raw.githubusercontent.com/I2djs/I2D/master/dist/i2d.min.js) 

## Initialising

To begin, we need container in which context will be rendered.

``` <div id="container"> </div> ```

### i2D Layer creation

For SVG Layer:
  ```javascript
    var svgRenderer = i2D.SVGLayer(containerId,config)
  ```
  
For Canvas Layer: 
   ```javascript
    var canvasRenderer = i2D.CanvasLayer(containerId,config)
  ```
  As many layers as needed can be created using above syntax. 
    
