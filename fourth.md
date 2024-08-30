# Cortex AI Tech - Frontend Notes
## 4th Lecture (28-08-2024)
### textarea tag
```
<textarea>
Used for forms with large amounts of text.
</textarea>
```
### img, map, area

``` 
These HTML tags are used to define a client-side image map. These allows you to create clickable areas within an image. When a user clicks on a defined area, the specified action (e.g., linking to a URL, opening a new window) is triggered.

Format:

1. Create an <img> element: Specify the image source using the src attribute.
2. Create a <map> element: Give it a unique name attribute.
3. Define areas within the <map>: Use <area> tags to specify the shape (rect, circle, poly), coordinates, and action (href) for each clickable area.
```

### Inline CSS
* Applies styles directly to individual HTML elements using the style attribute.
* Quick and easy but can clutter code.
* Best for small, temporary changes.
* Use external stylesheets for larger projects.

### Internal CSS
* Applies styles within the < head > section of an HTML document using the < style > tag.
* Provides better organization than inline CSS.
* Useful for styling multiple elements with the same styles.

### External CSS
* Applies styles in a separate .css file linked to the HTML document using the < link > tag.
* Provides the best organization and maintainability.
* Ideal for large projects with complex styling requirements.
### id Attribute
* Used to uniquely identify an HTML element within a document.
* Can be used with any HTML element.
* Allows you to target specific elements for styling or scripting.
* Must be unique within the document.
### class attribute
* Used to group multiple HTML elements with the same style or behavior.
* Can be applied to any HTML element.
* Allows you to apply styles or scripts to a group of elements at once.
* Can be used multiple times within a document.
### Element Selector
* Selects all elements of a specific HTML tag.
* Example: h1 selects all < h1 > elements.

### Class Selector
* Selects all elements with a specific class attribute.
* Uses a dot (.) followed by the class name.
### ID Selector
* Selects a single element with a specific ID attribute.
* Uses a pound sign (#) followed by the ID name.
### Descendant Selector
* Selects all elements that are descendants of a specific element.
* Uses a space to separate the ancestor element from the descendant element.
* Example: div p 

All < p > elements that are descendants of < div > elements will be selected.
### Child Selector
* Selects all elements that are direct children of a specific element.
* Uses a greater-than sign (>) to separate the parent element from the child element.
* Example: div > p

In this example, only < p > elements that are direct children of < div > elements (not grandchildren or further descendants) will be selected.
