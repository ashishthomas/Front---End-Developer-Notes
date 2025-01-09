## JavaScript Basic Interview Questions and Answers

## 1. What is javascript?

<p> Javascript is a programming language, it is used for interacting the webpages, supporting both client-side and server side development and integrating seamlessly with <b> HTML </b> and <b> CSS </b>. It is also used on the server-side using environements like Node.js </p>
<ol> Javascript is a single threaded language that executes one task at a time. </ol>
<ol> It is an interpreted language which means it executes the code line by line </ol>

## 2. How do you comment the line in Javascript?

<p> comments are used to add notes to your code in the execution. It has single line and multi - line of code.  </p>
<ol> multi-line code represents in /* */ </ol>

## 3. what is strict mode in javascript?

<details> <summary> Answers </summary> 
<p> <b> Strict Mode </b> in javascript is a way to make your code more secure and less error-prone. </p>
<ol> It helps catch common mistakes (e.g., using undeclared variables). </ol>
<ol> Prevents you from using certain unsafe features of JavaScript. </ol>
<ol> Makes debugging easier by showing errors that would otherwise be ignored. </ol>
<ol> To enable strict mode add “use strict”; at the top of a script or function. </ol>
</details>

```javascript
"use strict";
x = 10;
cosole.log(x);
```

## 4. what are the different datatypes in javascript ?

<details> <summary> Answers </summary>
<p> Javascript datatypes are of 2 types they are: </p>
<b> Primitive Datatypes </b>
<p> it has 7 primitive datatypes: </p>
    <ol> Number </ol>
    <ol> String </ol>
    <ol> Boolean </ol>
    <ol> Undefined </ol>
    <ol> Null </ol>
    <ol> Symbol (ES6) </ol>
    <ol> BigInt (ES11) </ol>

<p> it has various non - primitve datatypes: </p>
    <ol> Objects </ol>
    <ol> Arrays </ol>
    <ol> Functions </ol>
</details>

```javascript
let a = 5; // primitve
let b = a; // copy of the value
b = 10;
console.log(a);

let x = { name: "ashish" }; // non-primitve
let y = x; // reference to the same object
y.name = "Thomas";
console.log(x.name);
```

## 5. what is the difference between var, let and const ?

<details> <summary>  Answers </summary>
var: Function-scoped, can be re-declared and updated, hoisted.
let: Block-scoped, cannot be re-declared but can be updated, not initialized until the declaration is reached.
const: Block-scoped, cannot be re-declared or updated, must be initialized at the time of declaration.
</details>
