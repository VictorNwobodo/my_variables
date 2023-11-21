Introduction
JavaScript variables are containers for storing data values. They play a crucial role in programming by allowing you to store, retrieve, and manipulate information within your scripts. This guide covers the fundamental aspects of working with variables in JavaScript.

Declaring Variables
In JavaScript, variables are declared using the var, let, or const keywords. Each has its own implications for variable scope and mutability:

var: Declares a variable with function-level scope.
let: Introduces block-scoped variables, allowing for more precise control over variable scope.
const: Declares a constant variable with block scope; its value cannot be reassigned.


// Examples
var x = 10;
let y = 'Hello';
const PI = 3.14;


Data Types
JavaScript is a dynamically typed language, meaning variables can hold values of different types. The basic data types include:

Primitive Types:
Number: Numeric values.
String: Textual values.
Boolean: True or false values.
Undefined: Represents an uninitialized variable.
Null: Represents the intentional absence of any object value.
Object Types:
Object: A collection of key-value pairs.
Array: An ordered list of values.
Function: A reusable set of statements.



// Examples
let num = 42;
let str = 'Hello, World!';
let bool = true;
let arr = [1, 2, 3];
let obj = { key: 'value' };
Variable Scope
Understanding variable scope is crucial for preventing unintended side effects and managing the lifetime of variables. JavaScript has function-scoped variables with the var keyword and block-scoped variables with let and const.


// Function-scoped variable
function exampleFunction() {
  var localVar = 'I am a local variable';
  // localVar is accessible here
}
// localVar is not accessible here

// Block-scoped variable
if (true) {
  let blockVar = 'I am a block-scoped variable';
  // blockVar is accessible here
}

