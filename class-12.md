# Reading 12: Docs for the HTML <canvas> Element & Chart.js

## [Easily Create Stunning Animated Charts with Chart.js](https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js/)

* Chart.js makes it easy to create a chart on page by using the `<canvas>` tag in HTML5 and a JavaScript plugin
* Can create many different types of charts (in this article it was line, pie and bar charts)
* Things needed to use Chart.js are:
  * Chart.min.js (mini Chart.js file)
  * `<canvas>` element
  * `<script>` that includes a window into the DOM
  * data for the chart

### For more information about [Chart.js](https://www.chartjs.org/docs/latest/)

## [MDN: Basic Usage of Canvas](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Basic_usage)

* If no width or height values have been set, by default, `<canvas>` element has width of 300px and height of 150px
* Can be styled like an image
* should always have fallback content to allow the content in the `<canvas>` element to be seen in older browsers
* requires a closing `</canvas>` tag
* for `<canvas>` to render content it needs the `getContext()` method

## [MDN: Drawing Shapes with Canvas](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes)

* `<canvas>` can be used for drawing
* Grid: has (x,y) coordinates and starts at (0,0) at the top left corner with 1 unit = 1px
* Rectangles can be drawn by using 3 functions:
  * `fillRect(x, y, width, height)`: Draws a filled rectangle
  * `strokeRect(x, y, width, height)`: Draws a rectangular outline
  * `clearRect(x, y, width, height)`: Clears the specified rectangular area, making it fully transparent
* Can draw different shapes with `beginPath()`, `closePath()`, `stroke()`, `fill()`
* `moveTo(x, y)` is used with paths and acts like lifting a pen and moving it to another area to begin drawing
* `lineTo(x, y)` draws a line from point A (x,y) to point B (x,y)
* `arc()` and `arcTo()` used to draw arcs or circles
* `quadraticCurveTo()` and `bezierCurveTo()` used to draw quadratic and cubic Bézier curves
* `Path2D()` is a constructor that can be used to repeat a drawing by creating it as an object

## [MDN: Applying Styles and Colors](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Applying_styles_and_colors)

* `fillStyle = color` used to fill shapes with color
* `strokeStyle = color` used to style the shape's outline color
* `globalAlpha` used to assign semi-transparent color
* Gradients can also be created using `createLinearGradient()`, `createRadialGradient()`, and `createConicGradient()`

## [MDN: Drawing Text](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_text)

* `<canvas>` can also be used to draw text
* `fillText()` and `strokeText()` used to render text
* text can also be styled
* text can be measured using `measureText()` that returns a `TextMetrics` object that gives width of the text in pixels