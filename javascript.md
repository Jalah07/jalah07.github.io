## What is JavaScript?
JavaScript is a programming language that can be used for client-side and server-side. It allows you that make your web pages interactive. You can do things like making a search bar, automatically refreshing a page or animate images. JavaScript can update and change both HTML and CSS. It can calculate, manipulate, and validate data. It is supported by all major browsers.

## JavaScript Basics

String - A string may have zero or more characters, there’s no separate single-character type. It has double("") or single('') quotes.
Number - for numbers of any kind: integer or floating-point, integers are limited by ±(253-1).
Boolean - true/false
Array -  Arrays to store ordered collections.
Function - They allow the code to be called many times without repetition.
Variable -  used to store this information.
Comments - Single line comments start with `//`.

### How to make a variable
`let name = "Jalah";` allows you to declare variables that are limited to the scope of a block statement, or expression on which it is used
`const x = 0;` The value of a constant can't be changed through reassignment, and it can't be redeclared.

### Math with JavaScript

### JavaScript Arithmetic Operators
-	Addition(+)
-	Subtraction(-)
-	Multiplication(*)
-	Exponentiation(**)
-	Division(/)
-	Modulus (%)
-	Increment(++)
-	Decrement(--)

let a = 7;         // assign the value 7 to a
let b = 2;         // assign the value 3 to b
let c = a + b;     // c equals 9

## Examples of JavaScript in Action

### HTML
`<button id="btn">Press Me</button>`

### JavaScript
`document.getElementById("btn").addEventListener("click", function() {
    alert("You pressed me");
}`
