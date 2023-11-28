# Lesson 3.2: DOM Intro & Storing HTML

## JavaScript & HTML DOM:
- When a webpage loads, the browser creates a **Document Object Model (DOM)** of the page. 
- The DOM represents the blueprint of a webpage, structured like a tree of objects.

## DOM & JavaScript:

Referencing the HTML example below:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My title</title>
  </head>
  <body>
    <h1>A heading</h1>
    <a href="">Link text</a>
  </body>
</html>
```

With JavaScript, we can:

- Access the DOM.
- Declare variables to store HTML elements.
- Modify the HTML elements, attributes, and styles.
- Pair with event handlers to make websites interactive.


## Storing HTML Elements:

### Accessing Elements:

- The `document` object represents the whole webpage.
- To manipulate, we first access the document object, and then the specific HTML element.

**Key Point:** Variables can store numbers, strings, and also **HTML tags**. Storing HTML tags allows us to manipulate the HTML and CSS using JavaScript.

#### Using `querySelector()`:

```javascript
let paragraph = document.querySelector("p");
```

To access the DOM and store HTML:

1. Declare a variable.
2. Access the DOM with `document.querySelector()`.
3. Specify the selector in quotes:

- Using the HTML tag name: `"div"`
- Using the class: `".my-div"`
- Using the ID: `"#myDiv"`

Example:

```javascript
let var1 = document.querySelector("div");
let var2 = document.querySelector(".my-div");
let var3 = document.querySelector("#myDiv");
```

Remember: `querySelector()` only gets the FIRST matching HTML element.

