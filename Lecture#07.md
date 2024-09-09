# Cortex AI Tech - Frontend Notes
## 6th Lecture (02-09-2024)
### Text Align in CSS
The text-align property in CSS specifies the horizontal alignment of text within an element. It controls how the text is positioned relative to the element's width.
#### Syntax:
```
element {
  text-align: value;
}
```
#### Values:
* left: Aligns the text to the left edge of the element.
* center: Centers the text within the element.
* right: Aligns the text to the right edge of the element.
* justify: Justifies the text, spreading it out evenly across the entire width of the element.
* start: Aligns the text to the starting edge of the element (left in left-to-right languages, right in right-to-left languages).
* end: Aligns the text to the ending edge of the element (right in left-to-right languages, left in right-to-left languages).
### Text Decoration in CSS
The text-decoration property in CSS is used to add decorative effects to text, such as underlines, overlines, strikethroughs, and blinks.
#### Syntax
```
element {
  text-decoration: value;
}
```
#### Values:
* none: Removes all text decorations.
* underline: Adds an underline to the text.
* overline: Adds an overline to the text.
* line-through: Adds a strikethrough to the text.
* blink: Causes the text to blink (not recommended for general use).
### Text Indent in CSS
The text-indent property in CSS specifies the indentation of the first line of text within an element. It allows you to create hanging indents or outdents.
#### Syntax:
```
element {
  text-indent: value;
}
```
### Example:
```
p {
  text-indent: 50px;
}
```
### Line Height in CSS
The line-height property in CSS specifies the height of a line of text, including the space above and below the text. It controls the vertical spacing between lines.
#### Syntax:
```
element {
  line-height: value;
}
```
#### Example:
A unitless number representing the ratio of the line height to the font size. For example, a value of 1.5 means the line height is 1.5 times the font size.
```
p {
  line-height: 1.5;
}
```
### Letter Spacing in CSS
The letter-spacing property in CSS specifies the spacing between individual letters within a word. It allows you to adjust the distance between characters, creating effects like condensed or expanded text.
#### Syntax:
```
element {
  letter-spacing: value;
}
```
#### Example:
```
h1 {
  letter-spacing: 2px;
}
```
### Word Spacing in CSS
The word-spacing property in CSS specifies the spacing between words within a line of text. It allows you to adjust the distance between words, creating effects like condensed or expanded text.
#### Syntax:
```
element {
  word-spacing: value;
}
```
#### Example:
```
p {
  word-spacing: 5px;
}
```
### Font Family in CSS
The font-family property in CSS specifies the font to be used for text within an element. It allows you to choose from a variety of fonts, including system fonts and custom fonts.
#### Syntax:
```
element {
  font-family: font-name1, font-name2, ...;
}
```
#### Example:
```
body {
  font-family: Arial, sans-serif;
}
```
### Font Size in CSS
The font-size property in CSS specifies the size of the text within an element. It allows you to control the font size, making the text larger or smaller.
#### Syntax:
```
element {
  font-size: value;
}
```
#### Example:
```
h1 {
  font-size: 24px;
}
```
### Font Weight in CSS
The font-weight property in CSS specifies the thickness or boldness of the font. It controls the weight or heaviness of the text.
#### Syntax:
```
element {
  font-weight: value;
}
```
#### Values:
* normal: The default font weight, typically equivalent to 400.
* bold: A bolder weight, typically equivalent to 700.
* bolder: A bolder weight than the parent element's font.
* lighter: A lighter weight than the parent element's font.
* 100, 200, 300, 400, 500, 600, 700, 800, 900: Numeric values representing different font weights.
#### Example:
```
span {
  font-weight: 600;
}
```
### Font Awesome Icons
Font Awesome is a popular icon library that provides a vast collection of scalable vector icons. These icons are essentially fonts, allowing you to use them in your HTML and style them with CSS like any other text.
#### Include Font Awesome using CDN (Content Delivery Network):
```
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
```
#### Use Icons:
```
<i class="fa-home"></i>
```
