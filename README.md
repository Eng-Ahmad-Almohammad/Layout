# Layout
## Building Blocks
### CSS treats each HTML element as if it is in its own box. This box will either be a block-level box or an inline box.
![building block](https://user-images.githubusercontent.com/70091044/92462751-8b8eb380-f1d3-11ea-9fb6-9d0664d95635.PNG)
## Controlling the Position of Elements
### CSS has the following positioning schemes that allow you to control the layout of a page: normal flow, relative positioning, and absolute positioning. You specify the positioning scheme using the position property in CSS. You can also float elements using the float property.
- [ ] *Normal flow* (position:static)
### In normal flow, each block-level element sits on top of the next one. Since this is the default way in which browsers treat HTML elements, you do not need a CSS property to indicate that elements should appear in normal flow.
- [ ] *Relative Positioning* (position:relative)
### Relative positioning moves an element in relation to where it would have been in normal flow.
- [ ] *Absolute Positioning* (position:absolute)
### When the position property is given a value of absolute, the box is taken out of normal flow and no longer affects the position of other elements on the page. (They act like it is not there.) 
- [ ] *Fixed Positioning* (position:fixed)
### Fixed positioning is a type of absolute positioning that requires the position property to have a value of fixed. It positions the element in relation to the browser window. Therefore, when a user scrolls down the page, it stays in the exact same place. 
## Overlapping Elements (z-index)
### When you use relative, fixed, or absolute positioning, boxes can overlap. If boxes do overlap, the elements that appear later in the HTML code sit on top of those that are earlier in the page. If you want to control which element sits on top, you can use the z-index property. Its value is a number, and the higher the number the closer that element is to the front.
![Z-index](https://user-images.githubusercontent.com/70091044/92497820-7ed58400-f202-11ea-8f41-9a18fd10011b.PNG)
## Floating Elements (float)
### The float property allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible. Anything else that sits inside the containing element will flow around the element that is floated.
