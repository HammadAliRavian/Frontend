# Cortex AI Tech - Frontend Notes
## 8th Lecture (04-09-2024)
### Link States in CSS
Link states refer to the different visual appearances of a hyperlink based on its current state. CSS allows you to customize the style of links based on whether they are visited, hovered over, active, or focused.
#### Common Link States:
* a:link: Styles for unvisited links.
* a:visited: Styles for visited links.
* a:hover: Styles for links when the mouse pointer is hovering over them.
* a:active: Styles for links when they are clicked or tapped.
* a:focus: Styles for links when they are focused (e.g., when using a keyboard to navigate).
#### Examples:
```
a:link {
  color: blue;
  text-decoration: underline;
}

a:visited {
  color: purple;
}

a:hover {
  color: red;
}

a:active {
  color: green;
  text-decoration: none;
}
```
#### Order Matters:
Order: The order of link state selectors matters. The :link and :visited states should generally come before the :hover and :active states.
### Display None Property
The display: none property in CSS is used to completely hide an element from the page. It removes the element from the document flow, making it invisible to users and screen readers.
#### Syntax:
```
element {
  display: none;
}
```
#### Example:
```
#hiddenElement {
  display: none;
}
```
### Visibility Hidden Property
The visibility: hidden property in CSS makes an element invisible while still reserving its space in the document layout. Unlike display: none, which completely removes the element from the document flow, visibility: hidden hides the element without affecting the layout of other elements on the page.
#### Syntax:
```
element {
  visibility: hidden;
}
```
#### Example:
```
#hiddenElement {
  visibility: hidden;
}
```
### Position Properties in CSS
The position property in CSS determines the positioning of an element relative to its parent or to the viewport. It allows you to control the placement of elements on a web page, creating various layout effects.
#### Syntax:
```
element {
  position: value;
}
```
#### Values:
* static: The default value. Elements are positioned according to the normal flow of the document.
* relative: Elements are positioned relative to their normal position. The top, right, bottom, and left properties can be used to offset the element from its original position.   
* absolute: Elements are positioned relative to the nearest ancestor element with a position value other than static (or to the initial containing block if no such ancestor exists). The top, right, bottom, and left properties are used to position the element absolutely.
* fixed: Elements are positioned relative to the viewport. The top, right, bottom, and left properties are used to position the element relative to the viewport, creating elements that remain fixed in place even when the page is scrolled.
* Elements that are initially positioned according to the normal flow of the document, but become fixed when they reach a certain threshold within their container. This allows you to create elements that stick to the top or bottom of the viewport or their container, providing a fixed positioning effect while maintaining their original position within the document flow.
#### Examples:
1. Relative Positioning:
```
.element {
  position: relative;
  top: 20px;
  left: 50px;
}
```
2. Absolute Positioning:
```
.element {
  position: absolute;
  top: 100px;
  right: 20px;
}
```
3. Fixed Positioning:
```
.element {
  position: fixed;
  bottom: 20px;
  right: 20px;
}
```
4. Position Sticky Property
```
.element {
  position: sticky;
  top: 0; /* or bottom, left, or right */
}
```
### Z - Index Property
The z-index property in CSS controls the stacking order of elements that overlap. Elements with higher z-index values appear on top of elements with lower z-index values.
#### Syntax:
```
element {
  z-index: value;
}
```
#### Examples:
```
.element1 {
  z-index: 2;
}

.element2 {
  z-index: 1;
}
```
