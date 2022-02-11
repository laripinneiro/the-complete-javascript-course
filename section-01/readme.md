# JavaScript Fundamentals - Part I

## A Brief Introduction to JavaScript

JavaScript is a high level, object-oriented, multi-paradigm programming language.

- **Programming Language:** instruct computer to do things;

- **High-level:** we don't have to worry about complex stuff like memory management;

- **Object-oriented:** based on objects, for storing most kind of data;

- **Multi-paradigm:** we can use different styles of programming, such as imperative (how to do things) and declarative (what to do) programming.

We can use JS to build front-end apps, like create dynamic effects and web applications in the browser, back-end apps, like web applications on web server, and native mobile or desktop applications.

## Values and Variables

A **value** is basically the smallest unit of information that we have in JS, and **variable** stores the data value, that can be changed along scripting. When we declare a variable, there are some naming conventions:

- **camelCase:** when we have different words, those in the middle of the name begins with a capital letter;

- **numbers:** the name can receive numbers, but cannot be the first character;

- **symbols:** the only symbols that the name can receive are underscore and dollar sign;

- **keywords:** we cannot name a variable with JS keywords.

## Data Types

JS has primitive and reference types, the difference between is that when we have primitive types variable holds its actual value, but if it's a reference type the variable holds only references to the value.

JS has seven primitive data types: **number**, **string**, **boolean**, **undefined** (empty value), **null** (empty value with assignment), **symbol** and **bigInt**. Also it has dynamic typing so we don't have to manually define a value data type and we can change variable's value and its type.

If we wanna know the type of a value we can use **typeof**, like this:

```js
let a = 10;
console.log(typeof a); // number
console.log(typeof "javascript"); // string
```
