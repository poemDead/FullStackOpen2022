[mozilla css tutorial](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics)
Record: 0.5h - 04221422-04221451
======================
# CSS Basics
- CSS is short for Cascading Style Sheets. A style sheet language(not a programming language) which can style the web content.
- You can use `<link href="styles/style.css" rel="stylesheet">` to link your html to a css file.
- The CSS ruleset(element?)
    p {
        color: red;
    }
    - Selector `p`
    - A declaration which have several sets of property `color`and property value `red`.
- Different type of Selectors
    - Element Selector : select a html element directly
    - ID selector : `#the-id` select html element with specific **id** attribute.
    - Class selector : `.class-name` select html element with specific **class** attribute.
    - Attribute selector : `img[src]` select element with the specified attribute.
    - Pseudo-class selector : like `a:hover` select `<a>` but only when mouse pointer is hovering over the link.
- Fonts and text
    - use `<link>` in `<head>` can load this font family with the webpage
    - use something like this `font-family: "Open Sans", sans-serif;` in css file to change the font for  selected elements.
    - `font-size` for text size
    - `text-align`, `line-height`, `letter-spacing` to make the content more readable.
- CSS Box
    - CSS is all about boxes. Most HTML elements is just boxes stack together.
    - each box has properties like `padding`, `border`, `margin`.
    - also `width`, `backgroud-color`, `color`, `text-shadow`, `display`
    