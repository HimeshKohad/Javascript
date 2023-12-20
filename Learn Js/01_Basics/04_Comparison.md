# Day 4: Basics/Comparison.js

In today's learning, we focus on comparison operations in JavaScript and explore some peculiar cases that may cause confusion.

## Basic Comparisons

```javascript
console.log(2 > 1);
console.log(2 >= 1);
console.log(2 < 1);
console.log(2 == 1);
console.log(2 != 1);
```

## String Comparison

```javascript
console.log("2" > 1); // Output: true (string "2" is converted to a number)
console.log("02" > 1); // Output: false (string "02" is converted to a number)
```

### Caution with Type Conversions
Avoid relying on implicit type conversions, as they may lead to unexpected results.

```javascript
console.log(null > 0); // Output: false
console.log(null == 0); // Output: false
console.log(null >= 0); // Output: true
```

```javascript
console.log(undefined == 0); // Output: false
console.log(undefined > 0); // Output: false
console.log(undefined < 0); // Output: false
```

### Strict Equality (===)

```javascript
console.log("2" === 2); // Output: false (strict equality checks value and type)
```

<hr>

## Other Types of Comparisons

### Strict Inequality (!==)
The strict inequality operator checks for both value and type.

```javascript
console.log("2" !== 2); // Output: true
```

### Logical AND (&&) and Logical OR (||)
```javascript
let condition1 = true;
let condition2 = false;

console.log(condition1 && condition2); // Output: false (logical AND)
console.log(condition1 || condition2); // Output: true (logical OR)
```

### Ternary Operator (Conditional Operator)
```javascript
let result = (condition1) ? "true case" : "false case";
console.log(result); // Output: "true case"
```

_Understanding these comparison operations is crucial for making decisions in your JavaScript code. Always be mindful of type conversions and use strict equality when needed._
