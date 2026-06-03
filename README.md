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

Template literals are strings enclosed in backticks (`  `) that allow variable interpolation and multi-line strings.

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


