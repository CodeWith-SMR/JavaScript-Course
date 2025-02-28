# Introduction to JavaScript

## What is JavaScript?
JavaScript is a powerful and widely-used programming language that allows developers to create dynamic and interactive web applications. It is commonly used for:

- Adding interactivity to websites (e.g., buttons, forms, animations)
- Manipulating HTML & CSS dynamically
- Building full-stack applications with frameworks like React, Angular, and Node.js

### Why Learn JavaScript?
JavaScript is essential for web development because:
- It runs directly in the browser (client-side scripting)
- It can interact with HTML & CSS to create dynamic UI changes
- It has vast community support and powerful libraries (like jQuery, React, and Vue.js)

### How JavaScript Works
JavaScript code runs inside a browser using a JavaScript engine. Some popular browsers and their JavaScript engines are:
- **Chrome** → V8 Engine
- **Firefox** → SpiderMonkey
- **Safari** → JavaScriptCore

### Writing Your First JavaScript Code
To write JavaScript, you can use:
1. **Inline JavaScript** (inside an HTML file)
2. **Internal JavaScript** (inside a `<script>` tag in HTML)
3. **External JavaScript File** (`.js` file)

#### Example 1: Using JavaScript in HTML
```html
<!DOCTYPE html>
<html>
<head>
    <title>My First JS</title>
</head>
<body>
    <h1>Welcome to JavaScript</h1>
    <script>
        alert("Hello, JavaScript!");
    </script>
</body>
</html>
```

#### Example 2: Writing JavaScript in an External File
Create a file **`intro.js`** and add the following code:
```js
console.log("Welcome to JavaScript!");
alert("Hello from an external JS file!");
```
Now link this file in an HTML file like this:
```html
<script src="intro.js"></script>
```

### How to Run JavaScript?
1. **Browser Console:** Open Chrome, right-click → Inspect → Console.
2. **HTML file:** Write JavaScript inside `<script>` tags and open the HTML file.
3. **Node.js:** Install Node.js and run `node intro.js` in the terminal.

### Summary
- JavaScript makes websites dynamic and interactive.
- It runs inside browsers using JavaScript engines.
- You can write JavaScript inline, inside HTML, or in an external file.

Now, move to the next chapter to learn about **Variables in JavaScript!** 🚀