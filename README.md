# Software_Development_Assignment1
## Osho Elizabeth Kemi

# Programming Fundamentals

## 1. What is Programming, and Why is it Important in Software Development?
According to W3Schools, "Programming is telling a computer what to do."
**Source:** W3Schools. "Programming Intro." https://www.w3schools.com/programming/

Programming is the process of creating instructions that tell a computer how to execute specific tasks.

It is important because it enables developers to build software, automate processes, solve problems, and create applications that people use every day.

---

## 2. Explain the Three Stages of Programming: Think, Write, and Run & Iterate

### Think

Analyze the problem and plan a solution before writing any code. This stage involves understanding requirements, breaking down the problem, and designing an approach to solve it.

### Write

Transform the planned solution into code using a programming language. During this write stage, developers write instructions that the computer can understand and execute.

### Run & Iterate

Execute the program, test it, identify errors, fix issues, and improve the code. This process is repeated until the program works correctly and efficiently.

---
## 3. Why Should Code Be Written for Humans First and Machines Second?
Reasons why code should be written for human first because it helps developers to:
* Understand the code more easily.
* Debug and fix issues faster.
* Collaborate effectively with team members.
* Maintain and improve software over time.  
Computers can execute code regardless of readability. 

---

## 4. What Are Some Real-World Problems That Programming Can Solve?

Programming can be used to solve a wide range of real-world problems, which are:
**School Management Platforms**-  – Support student registration, grading and attendance tracking.
**Online Banking Systems** – Enable users to transfer money, pay bills, and manage accounts securely.
**Hospital Management Systems** – Help healthcare providers manage patient records, appointments, and treatments.
**E-commerce Websites** – Allow businesses to sell products and services online.
**Inventory Management Systems** – Track stock levels, sales, and product availability.
**Mobile Applications** – Provide solutions for communication, entertainment, education, and business needs.

# JavaScript Fundamentals

## 1. What is JavaScript, and Who Created It?

JavaScript is a programming language used to make web pages interactive and dynamic. It was created by Brendan Eich in 1995.

---

## 2. Briefly Explain the Evolution of JavaScript from 1995 to Today

### 1995

JavaScript was created by Brendan Eich at Netscape to add interactivity to web pages.

### 1997

JavaScript was standardized as ECMAScript, providing a common specification for the language.

### 2009

Node.js was introduced, allowing JavaScript to run on servers outside of web browsers.

### 2015

ECMAScript 2015 (ES6) introduced major improvements, including:

* `let` and `const`
* Arrow functions
* Classes
* Template literals
* Destructuring

### Today

JavaScript is one of the most widely used programming languages and is used for:

* Web development
* Mobile application development
* Desktop application development
* Server-side programming
* Cloud-based applications

---

## 3. List and Explain Four Environments Where JavaScript Can Run

### 1. Web Browsers

JavaScript runs directly in web browsers such as:

* Google Chrome
* Mozilla Firefox
* Microsoft Edge
* Safari

### 2. Node.js

Node.js allows JavaScript to run on servers, making it possible to build backend applications and APIs.

### 3. Mobile Applications

JavaScript can be used to develop mobile applications through frameworks such as React Native.

### 4. Desktop Applications
---

## 4. What is ECMAScript?

ECMAScript is the official standard specification upon which JavaScript is based. It defines the language's syntax, features, and behavior to ensure consistency across different JavaScript environments.

---

## 5. What Role Did Node.js Play in JavaScript's Growth?

The role of Node.js in JavaScript growth is that Node.js allow JavaScript to run outside web browsers, making it possible to build backend servers and full-stack applications using a single programming language.
As a result, developers can now use JavaScript for both front-end and back-end development.

# Variables and Data Types

## 1. Explain the Difference Between `var`, `let`, and `const`

| Keyword | Scope          | Reassignable | Redeclarable |
| ------- | -------------- | ------------ | ------------ |
| `var`   | Function Scope | Yes          | Yes          |
| `let`   | Block Scope    | Yes          | No           |
| `const` | Block Scope    | No           | No           |

### Explanation

* **`var`** is function-scoped and can be reassigned and redeclared.
* **`let`** is block-scoped and can be reassigned but cannot be redeclared within the same scope.
* **`const`** is block-scoped and cannot be reassigned or redeclared after its initial assignment.

---

## 2. Why is `const` Preferred in Modern JavaScript?

`const` is preferred because it:

* Prevents accidental reassignment.
* Makes code more predictable.
* Improves readability and maintainability.
* Helps reduce bugs caused by unintended changes to variable values.

---

## 3. Define the Following Primitive Data Types

### String

A string represents text values.

```javascript
let name = "Elizabeth";
```

### Number

A number represents numeric values.

```javascript
let age = 10;
```

### Boolean

A boolean represents one of two values: `true` or `false`.

```javascript
let isLoggedIn = true;
```

### Null

`null` represents an intentional absence of value.

```javascript
let user = null;
```

### Undefined

`undefined` represents a variable that has been declared but no value has been assigned.

```javascript
let city;
```
---

## 4. What Does the `typeof` Operator Do?

The `typeof` operator returns the data type of a value.

### Examples

```javascript
typeof "Hello"; // string
typeof 100;     // number
typeof true;    // boolean
```
---

## 5. What Are Template Literals and Why Are They Useful?

Template literals are strings enclosed in backticks (`) that allow variable interpolation and multi-line strings.

### Example

```javascript
let name = "ELizabeth";

console.log(`Hello, ${name}`);
```

### Output

```text
Hello, Elizabeth
```

### Benefits of Template Literals

Benefits of template literals are as follows:
* Easier string interpolation using `${}`.
* Improved readability.
* Support for multi-line strings.
* Cleaner and more maintainable code compared to traditional string concatenation.

# Functions and Control Flow

## 1. What Is a Function?

A function is a reusable building block of code designed to perform a specific task. Functions help organize code, improve readability, and reduce repetition.

### Example

```javascript
function greet() {
  console.log("Hello");
}
```

---

## 2. Compare Traditional Functions and Arrow Functions

### Traditional Function

```javascript
function add(a, b) {
  return a + b;
}
```

### Arrow Function

```javascript
const add = (a, b) => a + b;
```

### Differences

* Arrow functions have a shorter and more concise syntax.
* Arrow functions do not have their own `this` value; they inherit it from their surrounding scope.
  ### While
* Traditional functions are better when you need a dynamic `this` value.
* Traditional functions can be used as constructors, while arrow functions cannot.

---

## 3. What Are Default Parameters?

Default parameters provide fallback values when no argument is supplied to a function.

### Example

```javascript
function greet(name = "Guest") {
  return `Hello ${name}`;
}
```

### Explanation

from the above code it means if no value is passed to the `name` parameter, the function automatically uses `"Guest"` as the default value.

---

## 4. Explain the Purpose of Conditional Statements (`if`, `else if`, `else`)

Conditional statements allow programs to make decisions based on specific conditions.

### Example

```javascript
let score = 100;

if (score >= 80) {
  console.log("Pass");
} else {
  console.log("Fail");
}
```

### Explanation

In this example:

* If the score is 80 or higher, the program prints `"Pass"`.
* Otherwise, it prints `"Fail"`.

Conditional statements help control the flow of a program by executing different blocks of code depending on whether conditions are true or false.

---

## 5. What is a Loop, and When Would You Use One?

A loop repeatedly executes a block of code while a specified condition remains true.

### When will you use one  to Use Loops

### An example of the one I use

```javascript
for (let i = 1; i <= 10; i++) {
  console.log(i);
}
```
Using loops reduces code duplication and makes programs more efficient and easier to maintain.

---

# Modern JavaScript

## 1. What Is Destructuring?

Destructuring in JavaScript is a JavaScript feature that allows you to extract values from arrays or objects and assign them to variables in a concise or clear way.

### Example

```javascript
const person = {
  name: "Elizabeth",
  age: 10
};

const { name, age } = person;
```

### Explanation

In this example, the `name` and `age` properties are extracted from the `person` object and stored in variables with the same names.

---

## 2. Explain the Spread Operator and Rest Parameter

### Spread Operator (`...`)

The spread operator expands elements from an array or object.

### Example

```javascript
const nums = [1, 2, 3, 4];
const newNums = [....nums, 5];
```

### Result

```javascript
[1, 2, 3, 4, 5]
```

### Rest Parameter (`...`)

The rest parameter collects multiple arguments into a single array.

### Example

```javascript
function sum(...numbers) {
  return numbers;
}
```
### Explanation

The `numbers` parameter becomes an array containing all arguments passed to the function.

---

## 3. What Problem Does Optional Chaining Solve?

Optional chaining (`?.`) prevents errors when attempting to access properties that may not exist on an object.

### Example

```javascript
const user = {};

console.log(user.address?.city);
```

### Output

```javascript
undefined
```

### Explanation

Without optional chaining, JavaScript would throw an error because `address` does not exist. With optional chaining, the expression safely returns `undefined`.

---

## 4. What Are the Advantages of Async/Await Over Callbacks?

Async/Await provides a cleaner and more readable way to handle asynchronous operations.

### Advantages of Asyn/Await Over Callbacks

* It makes code easier to read and understand.
* Cleaner and more organized syntax.
* Better error handling using `try...catch`.
* Avoids deeply nested callback functions, commonly known as "callback hell."

### Example

```javascript
async function getData() {
  try {
    const data = await fetch(url);
  } catch (error) {
    console.log(error);
  }
}
```

---

## 5. Explain the Difference Between `map()` and `filter()`

### `map()`

The `map()` method transforms every element in an array and returns a new array containing the transformed values.

### Example

```javascript
const numbers = [1, 2, 3];
const doubled = numbers.map(num => num * 2);
```

### Result

```javascript
[2, 4, 6]
```

### `filter()`

The `filter()` method returns a new array containing only the elements that satisfy a specified condition.

### Example

```javascript
const numbers = [1, 2, 3, 4];
const even = numbers.filter(num => num % 2 === 0);
```

### Result

```javascript
[2, 4]
```

### Key Difference

* `map()` transforms every element in an array.
* `filter()` selects only elements that meet a condition.

---

## 6. Why Are ES6+ Features Important for Modern Development?

ES6 and later versions of JavaScript introduced features that make code more powerful, readable, and maintainable.

### Reasons why ES6+ Features Important for Modern Development are as follows:-

* Reduce code complexity.
* Improve readability and maintainability.
* Increase developer productivity.
* Introduce modern tools such as:

  * Classes
  * Modules
  * Promises
  * Async/Await
  * Destructuring
  * Arrow Functions
  * Template Literals
* Make JavaScript suitable for building large-scale and modern applications.


# Section B: JavaScript Practical Questions

## 1. Create Variables to Store Your Name, Age, and Favorite Programming Language. Print Them Using a Template Literal.

```javascript
const name = "Elizabeth";
const age = 10
const favouriteProgrammingLanguage = "JavaScript";

console.log(`My name is ${name}, I am ${age} years old, and my favourite programming language is ${favouriteProgrammingLanguage}.`);
```

### Output

```text
My name is Elizabeth, I am 10 years old, and my favourite programming language is JavaScript.
```

---

## 2. Write a Program That Checks Whether a Number Is Positive, Negative, or Zero.

```javascript
const number = 10;

if (number > 0)
    {console.log("Positive");}
else if (number < 0)
    {console.log("Negative");}
 else {console.log("Zero");}
```

### Output

```text
Positive
```

---

## 3. Create a Function Called `greetUser` That Accepts a Name and Returns a Greeting Message.

```javascript
function greetUser(name) {
  return `Hello, ${name}! Welcome.`;
}

console.log(greetUser("Elizabeth"));
```

### Output

```text
Hello, Elizabeth! Welcome.
```

---

## 4. Write an Arrow Function That Multiplies Two Numbers.

```javascript
const multiply = (x, y) => x * y;

console.log(multiply(8, 7));
```
### Output

```text
56
```

---

## 5. Create a Loop That Prints Numbers From 1 to 20.

```javascript
for (let i = 1; i <= 20; i++) {
  console.log(i);
}
```





