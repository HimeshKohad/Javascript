# Day 2: Basics/Datatypes.js

In today's learning, we delve into data types in JavaScript. The code provided covers various data types and their characteristics.

## Use Strict Mode

To ensure a more stringent interpretation of JavaScript, use strict mode.

Strict mode treats all code as newer version of JavaScript.

```javascript
"use strict";
```

## Console Output
In a Node.js environment, the **alert()** function is not available. Use console.log() to display output.

```javascript
console.log(3 + 3); // Output: 6
```

In a browser environment, you can use the **alert()** function to get the output as a popup on the screen.

```javascript
alert(2 + 3);
```

## Variables and Data Types
Declare variables and explore different data types.

```javascript
let name = "hello";
let age = 18;
let isLoggedIn = false;
```

## Data Types
JavaScript supports various data types:

- Number: Represents numeric values (up to 2 to the power 53).
- BigInt: Represents arbitrary precision integers.
- String: Represents textual data enclosed in double or single quotes.
- Boolean: Represents true or false values.
- Null: Represents a standalone value, often used to signify emptiness.
- Undefined: Represents a variable to which no value has been assigned.
- Symbol: Represents a unique identifier.

```javascript
// Additional Data Types
let bigNumber = 9007199254740991n; // BigInt
let message = "Hello, World!"; // String
let isValid = true; // Boolean
let emptyValue = null; // Null
let notAssigned; // Undefined
let uniqueId = Symbol("id"); // Symbol
```

## Checking Data Types
Use the typeof operator to check the data type of a variable.

```javascript
console.log(typeof age); // Output: number
console.log(typeof undefined); // Output: undefined
console.log(typeof null); // Output: object (Note: This is a historical quirk in JavaScript)
```

## Object
JavaScript also has an object data type, which is a complex data type that can store key-value pairs.

```javascript
let person = {
  name: "John",
  age: 30,
  isAdmin: false
};
```

_Remember to use the appropriate data type based on the kind of data you are working with to ensure clarity and consistency in your code._
