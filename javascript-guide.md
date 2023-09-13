# JavaScript Basics

JavaScript is a versatile and widely used programming language primarily used for web development. It allows you to create dynamic and interactive web applications. In this guide, we'll cover some fundamental concepts of JavaScript.

## 1. Hello, World!

Just like in Python, you can start with a simple "Hello, World!" program in JavaScript:

```javascript
console.log("Hello, World!");
```

This code will print "Hello, World!" to the browser's console.

## 2. Variables and Data Types

JavaScript supports various data types, including:

- **Number:** for numerical values (e.g., 42, 3.14)
- **String:** for text (e.g., "JavaScript", 'Hello')
- **Boolean:** for true or false values (e.g., true, false)
- **Array:** for ordered collections of values (e.g., [1, 2, 3])
- **Object:** for collections of key-value pairs (e.g., {name: "Alice", age: 25})

Here's how you can declare variables in JavaScript:

```javascript
let age = 25;
let name = "Alice";
let isStudent = true;
```

## 3. Basic Operations

You can perform arithmetic operations in JavaScript:

```javascript
let a = 10;
let b = 5;

// Addition
let result = a + b;

// Subtraction
result = a - b;

// Multiplication
result = a * b;

// Division
result = a / b;
```

## 4. Conditional Statements

JavaScript uses `if`, `else if`, and `else` statements for decision-making:

```javascript
let age = 18;

if (age < 18) {
    console.log("You are a minor.");
} else if (age === 18) {
    console.log("You just turned 18!");
} else {
    console.log("You are an adult.");
}
```

## 5. Loops

You can use `for` and `while` loops for iteration:

```javascript
// For loop
for (let i = 0; i < 5; i++) {
    console.log(i);
}

// While loop
let count = 0;
while (count < 5) {
    console.log(count);
    count++;
}
```

## 6. Functions

JavaScript allows you to define functions for reusable code:

```javascript
function greet(name) {
    console.log(`Hello, ${name}!`);
}

greet("Alice");
```

These are the basic concepts of JavaScript. JavaScript is an essential language for web development, and as you explore further, you'll encounter libraries and frameworks like React and Node.js that expand its capabilities. Happy coding!
