# Read 12

## Chart.js API
[Chart.js APT](https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js/)

Charts are a great visual tool compared to tables. Chart.js is a plugin that uses the HTML5 canvas element to draw the graph onto the page. In order to use it, you will need to download it then link up your HTML and JS with ```<script src='Chart.min.js'></script>```. With Chart.js you can draw a line chart, a pie chart, and a bar chart.

## Chart.js docs
[Chart.js docs](https://www.chartjs.org/docs/latest/)

You can download Chart.js from GitHub releases or use a Chart.js CDN. To start any chart, you would use ```<canvas>```. Remember to look over the contributing guidelines.

## Basic Usage
[Basic usage of canvas](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Basic_usage)

When using ```<canvas>```, you'll see it has two attributes, width and height. Note that if you size by CSS, it can appear distorted. It's a good idea to create an id so it's easier to identify in a script.

Fallback content is typically used when being displayed on older browsers not support HTML5. This should always be provided. Browsers that don't support ```<canvas>``` will look at the alternate content inside the element. Browsers that do support it will ignore the content inside.

```<canvas>``` creates a fixed-sized drawing surface. It exposes rendering contexts that are used to create and manipulate the content shown.

## Drawing shapes with canvas
[Drawing shapes with canvas](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes)

On canvas, there is a grid or coordinate space. 1 unit in the grid corresponds to 1 pixel on the canvas. The origin of the grid is positioned in the top left corner at (0,0). Elements are placed relative to this origin.

```<canvas>``` supports two shapes: rectangles and paths (points connected by a line). Other shapes are created by combining one or more paths.

Rectangles:
- fillRect(x, y, width, height)
- strokeRect(x, y, width, height)
- clearRect(x, y, width, height)

Paths:
- beginPath()
- closePath()
- stroke()
- fill()

Lines
- lineTo(x,y)

Arcs
- arc(x, y, radius, startAngle, endAngle, anticlockwise)
- arcTo(x1, y1, x2, y2, radius)

Path2D objects lets you cache or record these drawing commands.

## Applying styles and colors
[Applying styles and colors](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Applying_styles_and_colors)

How to apply colors to a shape:
1. fillStyle = color (sets the style used when filling shapes)
1. strokeStyle = color (sets the style for shapes' outlines)

You can also draw semi-transparent shapes using globalAlpha = transparencyValue. You can also draw using lines and gradients. There's also opportunities to use patterns.

## Drawing text
[Drawing Text](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_text)

You can draw text with using
- fillText(text, x, y [, maxWidth])
- strokeText(text, x, y [, maxWidth])

You can style text
- font = value
- textAlign = value
- textBaseline = value
- direction = value

[<== Back](https://simoneodegard.github.io/reading-notes/)