# Canvas

Canvas is a two-dimensional touch-sensitive rectangular panel on which drawing can be done and sprites can be moved.

The BackgroundColor, PaintColor, BackgroundImage, Width, and Height of the Canvas can be set in either the Designer or in the Blocks Editor. The Width and Height are measured in pixels and must be positive.

Any location on the Canvas can be specified as a pair of \(X, Y\) values, where

* X is the number of pixels away from the left edge of the Canvas
* Y is the number of pixels away from the top edge of the Canvas

There are events to tell when and where a Canvas has been touched or a Sprite\(ImageSpriteorBall\) has been dragged. There are also methods for drawing points, lines, and circles. Using this component, you can also draw shapes. Courtesy of [ColinTree](https://github.com/ColinTree), [HERE](https://github.com/mit-cml/appinventor-sources/files/1795587/DrawShape.DrawArc.zip) are 2 sample .aia that can be used to DrawShape and DrawArc onto Canvas component

 

## Properties

_**BackgroundColor**_

The color of the canvas background.

_**BackgroundImage**_

The name of a file containing the background image for the canvas

_**FontSize**_

The font size of text drawn on the canvas.

_**Height**_

_**LineWidth**_

The width of lines drawn on the canvas.

_**PaintColor**_

The color in which lines are drawn

_**TextAlignment**_

Determines the alignment of the text drawn by DrawText\(\) or DrawAngle\(\) with respect to the point specified by that command: point at the left of the text, point at the center of the text, or point at the right of the text.

_**Visible**_

Specifies whether the component should be visible on the screen. Value is true if the component is showing and false if hidden.

_**Width**_

## Events

**Dragged**\(number startX, number startY, number prevX, number prevY, number currentX, number currentY, boolean draggedSprite\)

When the user does a drag from one point \(prevX, prevY\) to another \(x, y\). The pair \(startX, startY\) indicates where the user first touched the screen, and "draggedSprite" indicates whether a sprite is being dragged.

**Flung**\(number x, number y, number speed, number heading, number xvel, number yvel, boolean flungSprite\)

When a fling gesture \(quick swipe\) is made on the canvas: provides the \(x,y\) position of the start of the fling, relative to the upper left of the canvas. Also provides the speed \(pixels per millisecond\) and heading \(0-360 degrees\) of the fling, as well as the x velocity and y velocity components of the fling's vector. The value "flungSprite" is true if a sprite was located near the the starting point of the fling gesture.

**TouchDown**\(number x, number y\)

When the user begins touching the canvas \(places finger on canvas and leaves it there\): provides the \(x,y\) position of the touch, relative to the upper left of the canvas

**TouchUp**\(number x, number y\)

When the user stops touching the canvas \(lifts finger after a TouchDown event\): provides the \(x,y\) position of the touch, relative to the upper left of the canvas

**Touched\(number x, number y, boolean touchedSprite\)**

When the user touches the canvas and then immediately lifts finger: provides the \(x,y\) position of the touch, relative to the upper left of the canvas. TouchedSprite is true if the same touch also touched a sprite, and false otherwise.

## Methods

_**Clear\(\)**_

Clears anything drawn on this Canvas but not any background color or image.

_**DrawCircle\(number x, number y, number r\)**_

Draws a circle \(filled in\) at the given coordinates on the canvas, with the given radius.

_**DrawLine\(number x1, number y1, number x2, number y2\)**_

Draws a line between the given coordinates on the canvas.

_**DrawPoint\(number x, number y\)**_

Draws a point at the given coordinates on the canvas.

_**DrawText\(text text, number x, number y\)**_

Draws the specified text relative to the specified coordinates using the values of the FontSize and TextAlignment properties.

_**DrawTextAtAngle\(text text, number x, number y, number angle\)**_

Draws the specified text starting at the specified coordinates at the specified angle using the values of the FontSize and TextAlignment properties.

_**number GetBackgroundPixelColor\(number x, number y\)**_

Gets the color of the specified point. This includes the background and any drawn points, lines, or circles but not sprites.

_**number GetPixelColor\(number x, number y\)**_

Gets the color of the specified point.

_**text Save\(\)**_

Saves a picture of this Canvas to the device's external storage. If an error occurs, the Screen's ErrorOccurred event will be called.

_**text SaveAs\(text fileName\)**_

Saves a picture of this Canvas to the device's external storage in the file named fileName. fileName must end with one of .jpg, .jpeg, or .png, which determines the file type.

_**SetBackgroundPixelColor\(number x, number y, number color\)**_

Sets the color of the specified point. This differs from DrawPoint by having an argument for color.

