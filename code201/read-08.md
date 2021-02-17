# read 08

## HTML Ch 15
HTML elements have their own box. These boxes are block-level (starts on a new line) or inline (will flow inbetween surrounding content).

CSS has positioning schemes that lets you control the layout of the page.
- **Normal flow** ```position: static``` The default flow. Paragraphs appear one after another vertically down.
- **Relative positioning** ```position: relative``` This shifts elements to the top, right, bottom, or left. This does not affect the position of surrounding elements. 
- **Absolute positioning** ```position: absolute``` The element position is in relation to the containing element.
- **Fixed positioning** ```position: fixed``` A form of absolute positions, however the element positioning changes in relation to the browser window.
- ***Overlapping elements** ```z-index``` Relative, fixed, and abolute positioning can all overlap. You can control which element sits on top. Z-index is sometimes called **stacking context**.
- **Floating elements** ```float``` When you float an element, it takes it out of the normal flow and position of a containing box. You can use float to put elements side by side. ```clear``` will make it so no element in the same containing element should touch.

**Screen sizes**
There are many different screen sizes. Designers will create pages to be 960-1000 pixels wide.

**Layouts**
- **Fixed width layout**
- **Liquid layout**
- **Layout grids**

**Multiple Style Sheets**
- **@import**
- **link**

[<== Back](https://simoneodegard.github.io/reading-notes/)