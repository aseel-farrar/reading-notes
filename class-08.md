# Read: 08 - More CSS Layout


## Building Blocks
* CSS treats each HTML element as if it is in its own box. This box will either be a ***block-level*** box or an ***inline*** box.

* Block-level boxes start on a new line and act as the main building blocks of any layout, while inline boxes flow between surrounding text.
* It is common to group a number of elements together inside a `<div>` elements, The `<div>` element that contains this group of elements is then referred to as the containing element.

* CSS has the following positioning schemes that allow you to control the layout of a page: 
  1. **normal flow**: Every block-level element appears on a new line, causing each item to appear lower down the page than the previous one.
  2. **relative Positioning**: moves an element from the position it would be in normal flow, shifting it to the top, right, bottom, or left of where it would have been placed
  3. **absolute Positioning**: positions the element in relation to its containing element (parent element).

* To indicate where a box should be positioned, you may also need to use *box offset* properties to tell the browser how far from the top or bottom and left or right it should be placed.

* ***fixed Positioning*** This is a form of absolute positioning that positions the element in relation to the browser window, as opposed to the containing element. Elements with fixed positioning do not affect the position of surrounding elements and they do not move when the user scrolls up or down the page.

* ***floating elements*** Floating an element allows you to take that element out of normal flow and position it to the far left or right of a containing box. The floated element becomes a block-level element around which other content can flow.

* When you move any element from normal flow, boxes can overlap. The `z-index` property allows you to control which box appears on top.

## screen sizes
Different visitors to your site will have different sized screens that show different amounts of information.

* **Fixed width layout** designs do not change size as the user increases or decreases the size of their browser window. Measurements tend to be given in pixels.
* **Liquid layout** designs stretch and contract as the user increases or decreases the size of their browser window. They tend to use percentages.




***

Go back

[Back](README.md)

