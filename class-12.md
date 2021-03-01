# Read: 12 - Docs for the HTML <canvas> Element & Chart.js

## HTML <canvas> 
*  `<canvas>` looks like the `<img>` element, with the only clear difference being that it doesn't have the *src* and *alt* attributes.
* `<canvas>` element has only two attributes, width and height, When no width and height attributes are specified, the canvas will initially be 300 pixels wide and 150 pixels high.
* requires the closing tag `</canvas>`.
* The `<canvas>` element can be styled just like any normal image (margin, border, background…).


## Chart.js
* Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool.
* They’re easier to look at and convey data quickly, but they’re not always easy to create.
* The great things about Chart.js are that it’s simple to use and really very flexible.
* required is the script included in your page along with a single `<canvas>` node to render the chart.
* Chart.js is available under the ***MIT license***.

## Applying styles and colors
* to apply colors to a shape, there are two important properties we can use:
1. `fillStyle = color` Sets the style used when filling shapes.
1. `strokeStyle = color`Sets the style for shapes outlines.

* There are several properties which allow us to style lines.

1. `lineWidth = value`: Sets the width of lines drawn in the future.
1. `lineCap = type`: Sets the appearance of the ends of lines.
1. `lineJoin = type`: Sets the appearance of the "corners" where lines meet.
1. `miterLimit = value`: Establishes a limit on the miter when two lines join at a sharp angle, to let you control how thick the junction becomes.
1. `getLineDash()`:Returns the current line dash pattern array containing an even number of non-negative numbers.
1. `setLineDash(segments)`:Sets the current line dash pattern.
1. `lineDashOffset = value`: Specifies where to start a dash array on a line.

* The `lineCap` property determines how the end points of every line are drawn. There are three possible values for this property and those are:
1. `butt`: The ends of lines are squared off at the endpoints.
1. `round`: The ends of lines are rounded.
1. `square`: The ends of lines are squared off by adding a box with an equal width and half the height of the line's thickness.
* The lineJoin property determines how two connecting segments (of lines, arcs or curves) with non-zero lengths in a shape are joined together (degenerate segments with zero lengths, whose specified endpoints and control points are exactly at the same position, are skipped). There are three possible values for this property: `round`, `bevel` and `miter`. By default this property is set to `miter`.
***

Go back

[Back](README.md)

