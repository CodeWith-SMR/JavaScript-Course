# Chapter 1: Hello, World!

## Introduction
Welcome to **Chapter 1: Hello, World!** In this chapter, we will learn how to write our first JavaScript program. The phrase **"Hello, World!"** is traditionally used to introduce a programming language because it is simple yet demonstrates how to output text.

By the end of this chapter, you will:
- Understand how JavaScript interacts with a web page.
- Learn how to use `console.log()` to print messages.
- Write your first JavaScript program.
- Get comfortable with basic syntax and concepts.

---

## Writing Your First JavaScript Program
To display **"Hello, World!"**, follow these steps:

### 1. Using `console.log()`
The `console.log()` method is used to print messages to the browser console.

#### Example:
```javascript
console.log("Hello, World!");
```

#### Explanation:
- `console.log()` is a built-in function in JavaScript that outputs text to the browser console.
- `"Hello, World!"` is the message we want to display.
- The semicolon `;` at the end of the line is optional but recommended.

### 2. Running JavaScript in a Browser
You can run this code in two ways:

#### Method 1: Using Browser Console
1. Open **Google Chrome** (or any browser).
2. Right-click anywhere on the page and select **Inspect**.
3. Go to the **Console** tab.
4. Type the following code and press **Enter**:
   ```javascript
   console.log("Hello, World!");
   ```
5. You will see `Hello, World!` printed in the console.

#### Method 2: Writing in an HTML File
You can also write JavaScript inside an HTML file:

```html
<!DOCTYPE html>
<html>
<head>
    <title>JavaScript Hello World</title>
</head>
<body>
    <script>
        console.log("Hello, World!");
    </script>
</body>
</html>
```

#### Explanation:
- `<script>` tags are used to insert JavaScript inside an HTML file.
- The code inside `<script>` will run when the page loads.
- Open this file in a browser and check the **console** to see the message.

---

## Understanding JavaScript Basics

### 1. Comments in JavaScript
Comments help you explain your code but do not affect execution.

```javascript
// This is a single-line comment
console.log("Hello, World!");

/*
   This is a multi-line comment
   It can span multiple lines
*/
```

### 2. Variables and Data Types
JavaScript allows storing values using **variables**.

```javascript
let message = "Hello, World!";
console.log(message);
```

#### Explanation:
- `let` is used to declare a variable.
- `"Hello, World!"` is a string (text) assigned to the variable `message`.
- `console.log(message);` prints the value of `message`.

---

## Assignments

### Task 1: Basic Console Output
Write a JavaScript program that prints **"Welcome to JavaScript!"** in the console.

### Task 2: Using Variables
Create a variable named `greeting` that stores **"Good Morning!"** and print it using `console.log()`.

### Task 3: Writing Comments
Write a JavaScript program that includes both **single-line** and **multi-line comments**.

### Task 4: Adding JavaScript to an HTML File
Create an HTML file and write JavaScript inside the `<script>` tag to print **"Learning JavaScript!"** in the console.

### Task 5: Experiment with Errors
Write a JavaScript program that contains an **intentional error** (e.g., missing a closing quote) and see what error message appears in the console.

---

## Summary
In this chapter, we learned:
- How to write and run JavaScript.
- Using `console.log()` to print messages.
- The importance of comments.
- Declaring variables and using them.

Congratulations! You have successfully written your first JavaScript program. 🎉
