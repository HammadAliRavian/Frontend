# Cortex AI Tech - Frontend Notes
## 6th Lecture (02-09-2024)
### CSS Comments
To add a comment to your CSS code, enclose the text within /* and */
#### Example:
```
/* This is a single-line comment */

/*
This is a
multi-line comment
*/
```
### Named Colors
CSS has a built-in list of named colors that represent specific hues.
* Examples: red, blue, green, yellow, orange, purple, pink, black, white, gray, etc.
### Hexadecimal Color Codes
Colors can also be represented using hexadecimal color codes, which consist of six characters (a combination of numbers and letters).
* Each pair of characters represents the intensity of red, green, and blue (RGB) in the color.
* Examples: #FF0000 (red), #0000FF (blue), #FFFF00 (yellow)
### RGB (Red, Green, Blue)
Colors can be defined using the rgb() function, which takes three arguments: the red, green, and blue components as integers between 0 and 255.
* Example: rgb(255, 0, 0) (red)
### HSL (Hue, Saturation, Lightness)
Colors can be defined using the hsl() function, which takes three arguments: hue (an angle on the color wheel), saturation (the intensity of the color), and lightness (the brightness of the color).
* Example: hsl(0, 100%, 50%) (red)
### CSS Opacity
Opacity in CSS refers to the transparency or visibility of an element. An opacity value of 0 means the element is completely transparent, while a value of 1 means it's completely opaque.
#### Example:
```
element {
  opacity: 0.5; /* 50% opacity */
}
```
### Block - Level Elements in CSS
Block-level elements occupy the entire width of their parent container and start on a new line. They are typically used to structure content and define layout.
#### Characteristics of Block-Level Elements
* Width: Block-level elements take up the full width of their parent container.
* Height: The height of a block-level element is determined by its content.
* Margin and Padding: Block-level elements can have margins and padding around them, which affect their spacing and layout.
* Display Property: The display property of block-level elements is typically set to block.
### Inline Elements in CSS
Inline elements do not start on a new line and only take up the space they need. They are typically used for text-based content and to create simple layouts.
#### Characteristics of Inline Elements
* Width: Inline elements only take up the width necessary to display their content.
* Height: The height of an inline element is determined by its font size and line height.
* Margin and Padding: Inline elements can have margins and padding, but they are applied differently than for block-level elements.
* Display Property: The display property of inline elements is typically set to inline.
### Inline - Block Elements in CSS
Inline-block elements combine the characteristics of both inline and block-level elements. They are displayed inline, but they can have their own width, height, margin, and padding. This makes them versatile for creating custom layouts.
#### Characteristics of Inline-Block Elements
* Display Property: Set the display property to inline-block.
* Width and Height: You can specify the width and height of inline-block elements using the width and height properties.
* Margin and Padding: Apply margins and padding to control the spacing around inline-block elements.
* Vertical Alignment: Use the vertical-align property to control the vertical alignment of inline-block elements within their parent container.
### max-width in CSS
The max-width property in CSS specifies the maximum width of an element. It ensures that the element's width will never exceed the specified value, even if the content or layout requires a larger width.
#### Example:
```
element {
  max-width: 200px;
}
```
### min-width in CSS
The min-width property in CSS specifies the minimum width of an element. It ensures that the element's width will never be smaller than the specified value, even if the content or layout requires a smaller width.
#### Example:
```
element {
  min-width: value;
}
```
### max-height in CSS
The max-height property in CSS specifies the maximum height of an element. It ensures that the element's height will never exceed the specified value, even if the content or layout requires a larger height.
#### Example:
```
element {
  max-height: value;
}
```
### min-height in CSS
The min-height property in CSS specifies the minimum height of an element. It ensures that the element's height will never be smaller than the specified value, even if the content or layout requires a smaller height.
#### Example:
```
element {
  min-height: value;
}
```
