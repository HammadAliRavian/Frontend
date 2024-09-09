# Cortex AI Tech - Frontend Notes
## 09th Lecture (05-09-2024)
### Overflow Property in CSS
The overflow property in CSS controls how content is handled when it exceeds the available space within an element. It allows you to specify what should happen when the content overflows the element's boundaries.
#### Syntax:
```
element {
  overflow: value;
}
```
#### Values:
* visible: (default) The content overflows the element's boundaries, and the overflowing content is visible.
* hidden: The overflowing content is clipped and hidden.
* scroll: A scrollbar is added to the element, allowing the user to scroll through the overflowing content.
* auto: A scrollbar is added only if the content overflows the element's boundaries.
#### Examples:
1. Hiding Overflowing Content:
```
.container {
  overflow: hidden;
}
```
2. Adding Scrollbars:
```
.text {
  overflow: scroll;
}
```
3. Automatic Scrollbars:
```
.image {
  overflow: auto;
}
```
### Float Property
The float property in CSS is used to position an element to the left or right side of its container, allowing it to wrap around other content. This creates a more flexible and dynamic layout for your web pages.
#### Syntax:
```
element {
  float: value;
}
```
#### Values:
* left: Positions the element to the left side of its container.
* right: Positions the element to the right side of its container.
* none: Removes the floating effect, returning the element to its normal position in the document flow.
#### Example:
```
img {
  float: left;
  margin-right: 10px;
}
```
### Display Flex Property
The display: flex property in CSS is used to create flexible box layouts, providing a powerful and efficient way to arrange elements on a page. It allows you to control the layout of elements, their spacing, alignment, and more.
#### Syntax:
```
element {
  display: flex;
}
```
#### Key Features
* Flex Container: The element with display: flex is called the flex container. It defines the layout for its child elements, which are called flex items.
* Flex Items: Child elements within a flex container are automatically arranged as flex items.
* Flex Direction: Controls the direction in which flex items are placed within the container. Options include row, row-reverse, column, and column-reverse.
* Justify Content: Controls the alignment of flex items along the main axis (horizontal or vertical). Options include flex-start, flex-end, center, space-between, and space-around.
* Align Items: Controls the alignment of flex items along the cross axis (vertical or horizontal). Options include flex-start, flex-end, center, stretch, and baseline.
## Specificity
### Factors Affecting Specificity
#### Inline Styles
Styles directly applied to an element using the style attribute have the highest specificity.
#### IDs
Styles applied to elements with unique IDs have a high specificity.
#### Classes
Styles applied to elements with classes have a medium specificity.
#### Elements
Styles applied to elements based on their tag names have the lowest specificity.
### Specificity Calculation
1. Points for inline styles: 1000 points
2. Points for IDs: 100 points
3. Points for classes: 10 points
4. Points for elements: 1 point
### Tips for Specificity
* Avoid Overly Specific Rules: Try to use more generic selectors to avoid specificity conflicts.
* Use the !important Declaration: The !important declaration can override any other rule, regardless of its specificity. However, use it sparingly as it can make your stylesheets less maintainable.
