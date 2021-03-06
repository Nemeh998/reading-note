# Chapter 15: Layout
### Key Concepts in Positioning Elements
* Building Blocks:
1. Block-level elements start on a new line ```<h1> <p> <ul> <li>```
* Inline elements flow in between surrounding text ```<img> <b> <i>```
Containing Elements: If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element. ```<div>```
### ```float``` property
* ```Normal flow``` Every block-level element appears on a new line, causing each item to appear lower down the page than the previous one.

* ```Relative Positioning``` This moves an element from the position it would be in normal flow, shifting it to the top, right, bottom, or left of where it would have been placed.

* ```Absolute positioning``` This positions the element in relation to its containing element. It is taken out of normal flow, meaning that it does not affect the position of any surrounding elements

* The ```z-index``` property allows to control which box appears on top.

## Position property in CSS
### Kyewords:
```position:static:``` default

```position:relative:``` moves an element in relation to where it would have been in normal flow.

```position:absolute:``` the box is taken out of normal flow and no longer affects the position of other elements on the page.

```position:fixed:```v a type of absolute positioning that requires the position property to have a value of fixed

![p](https://cdn-media-1.freecodecamp.org/images/Ium4uJdPRXPpp-gAVsMMWveviu6HY-g0nUYA)
____
z-index: to control which element sits on top.
___
float: to take an element in normal flow and place it as far to the left or right of the containing element as possible.
___
clear: to say that no element (within the same containing element) should touch the left or righthand sides of a box.
___
left
right
both
none
width This sets the width of the columns

float This positions the columns next to each other

margin This creates a gap between the columns.

Resolution refers to the number of dots a screen shows per inch.

Designers keep pages within 960-1000 pixels wide, and indicate what the site is about within the top 600 pixels (to demonstrate its relevance without scrolling).
Fixed width layout: designs do not change size as the user increases or decreases the size of their browser window. Measurements tend to be given in pixels.

Liquid layout designs: stretch and contract as the user increases or decreases the size of their browser window. They tend to use percentages.

Grid: the placement or arrangement of visual elements.

## Multiple Style Sheets
___
@import HTML page can link to one style sheet and that stylesheet can use the @import rule to import other style sheets.

```<link>``` HTML can use a separate element for each style sheet.