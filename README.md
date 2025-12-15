# University Course Management System

This project is a simple University Course Management System developed using JavaScript.  
It demonstrates the use of ES6 modules, classes, asynchronous callbacks, object immutability, and array manipulation.

---

## File Organization

- **main.js**  
  Entry point of the application.  
  Fetches student data asynchronously, tests immutability, and runs analytics functions.

- **model.js**  
  Contains the `Student` class.  
  The student ID is defined as immutable using `Object.defineProperty`.

- **database.js**  
  Simulates a slow database using `setTimeout` and asynchronous callbacks.

- **analytics.js**  
  Includes helper functions for:
  - Calculating class averages
  - Finding the top student
  - Filtering students using higher-order functions

- **package.json**  
  Project configuration file.  
  Configured to use ES modules.

---

## Features Implemented

- ES6 Classes
- Asynchronous callbacks
- Immutable object properties
- Array methods such as `map`, `filter`, and `reduce`
- Modular file structure

---

## Challenges Faced

- Configuring Node.js to correctly support ES modules (`import/export`)
- Understanding and resolving Git merge conflicts
- Managing GitHub synchronization issues during push and rebase
- Ensuring immutability of object properties without breaking the program flow

---

## How to Run the Project

1. Install Node.js
2. Open the project folder in VS Code
3. Run the following command in the terminal:

```bash
node main.js
