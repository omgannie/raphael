# RaphaëlJS

[http://dmitrybaranovskiy.github.io/raphael/](http://dmitrybaranovskiy.github.io/raphael/)

## Overview
RaphaelJS is a small JavaScript library created by Dmitry Baranovskiy significantly simplifies rendering vector graphics on the web.

Raphaël ['ræfeɪəl] uses the SVG W3C Recommendation and VML as a base for creating graphics. This means every graphical object you create is also a DOM object, so you can attach JavaScript event handlers or modify them later. Raphaël’s goal is to provide an adapter that will make drawing vector art compatible cross-browser and easy.

## Usage

```js
// Creates canvas 320 × 200 at 10, 50
var paper = Raphael(10, 50, 320, 200);

// Creates circle at x = 50, y = 40, with radius 10
var circle = paper.circle(50, 40, 10);
// Sets the fill attribute of the circle to red (#f00)
circle.attr("fill", "#f00");

// Sets the stroke attribute of the circle to white
circle.attr("stroke", "#fff");
```

## Demo
[http://dmitrybaranovskiy.github.io/raphael/tiger.html]
