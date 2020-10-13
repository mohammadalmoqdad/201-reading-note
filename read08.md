* CSS treats each HTML element as if it is in its own box. This box will either be a *block-level box* or an *inline box*.
*  the *containing* or *parent* element: 
  * it is happened If one block-level element sits inside another block-level element.
  * The containing element is always the direct parent of that element.
* positioning in css is trhee types:
  1. Normal flow: The elements being sorted one by one on the page.
  2. Relative Positioning: the surrounded elemnts flow will not be affected but the difference will be by the left & tight positioning.
  3. Absolute positioning: It is taken out of normal flow, and the elements position can be controlled perfectly.
* **Box offset** properties to tell the browser how far from the top or bottom and left or right it should be placed.
* **When you move any element from normal flow, boxes can overlap. The z-index property allows you to control which box appears on top.**
* There are three values of *position* atribute in CSS:
  1. `position:static`  : In normal flow, each block-level element sits on top of the next one. Since this is the default way in which browsers treat HTML elements
  2. `position:relative` : Relative positioning moves an element in relation to where it would have been in normal flow.
    * You then use the offset properties (top or bottom and left or right) to indicate how far to move the element from where it would have been in normal flow.
  3. `position:absolute` : the box is taken out of normal flow and no longer affects the position of other elements on the page. 
  4. `position:fixed` : Fixed positioning is a type of absolute positioning but It positions the element in relation to the browser window. Therefore, when a user scrolls down the page, it stays in the exact same place. 

* By default, most browsers add a margin to the top of the `<h1>`element. This is why there is a gap between the top of the browser and the box containing the `<h1>` element.
* ***z-index*** :it is a property to avoid overlapping of the elements in a way that may be not shown because **HTML code sit on top of those that are earlier in the page.** 
  * the higher z-index will be shown above the less.
* 