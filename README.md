## CSS
### Three ways to insert CSS
- Inline CSS (Not recommended)
- Internal CSS (Use style tag)
- External CSS (Use external .css file)

### CSS Selector
![css selector](./images/css_selector.jpg)

### Colors in CSS
- Color Names
- HTML5 color names
- Hexadecimal
- RGB

### Class in CSS
When class of element is declared, .css file is able to refer it by using `dot classname`

### margin & padding
- `margin: auto` in container makes equivalent space in browser.
- padding surround content and margin surround outter thing
- Possible to use clockwise notation to shorthand

### Box Model
![box model](./images/box_model.jpg)

### Apply everything in CSS
```CSS
/* Top of the file */
*{
  /* Here */
}
```

### Select Tag in Class
```CSS
.box-1 h1{
    /* Any h1 in this within this class */
}
```

### Positioning in CSS
- Static
- Relative
- Absolute
- Fixed
- Initial
- Inherit

---
## Flexbox in CSS
### What is Flexbox? 
A CSS3 layout mode that provides an easy and clean way to arrange items within a container.
- No floats
- Responsive and mobile friendly
- Positioning child elements is much easier
- Flex container's margins do not collapse with the margins of its contents
- Order of elements can easily be changed without editing the source HTML

### Flexible box model concept
- The ability to alter item width and height to best fit in its containers available free space
- Flexbox is direction-agnostic
- Built for small-scale layouts while the **Grid** specification is for more large scale

### Flexbox diagram
![diagram](./images/flexbox_diagram.jpg)
![container](./images/flex_container.jpg)
[more detail](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

### Result
![box model](./images/mywebpage.png)