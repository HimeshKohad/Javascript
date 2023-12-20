# Day 5: Basics/Datatypes-Summary.js

In today's learning, we explore primitive and reference (non-primitive) data types in JavaScript.

## Primitive Data Types

### String

```javascript
const score = 100;
const scoreValue = 100.3;
```

### Boolean

```javascript
const isLoggedIn = false;
```

### Null and Undefined

```javascript
const id = Symbol('123');
const anotherId = Symbol('123');
console.log(id === anotherId); // Output: false (symbols are unique)
```

### Symbol

```javascript
const id = Symbol('123');
const anotherId = Symbol('123');
console.log(id === anotherId); // Output: false (symbols are unique)
```

### BigInt

```javascript
const bigNumber = 9876543210123456789n;
```

## Reference (Non-Primitive) Data Types

### Array

```javascript
const heros = ["John", "Mark", "Sam"];
```

### Object

```javascript
let myObj = {
    name: "Jack",
    age: 32,
};
```

### Function

```javascript
const myFunction = function(){
    console.log("Hello world");
};
```

### Checking Data Type

```javascript
console.log(typeof anotherId); // Output: symbol
```

<hr>

## Additional Resources

For more details on data types in JavaScript, refer to the [official ECMAScript documentation](https://262.ecma-international.org/5.1/#sec-11.4.3).

_Understanding primitive and reference data types is fundamental for working with data efficiently in JavaScript. 
Always choose the appropriate data type based on the nature of the data you're dealing with._
