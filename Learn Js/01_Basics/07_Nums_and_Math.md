# 7. Nums and math.js

In today's learning, we explore number operations and the Math object in JavaScript.

## Working with Numbers

```javascript
const score = 900;
console.log(score);

const balance = new Number(100);
console.log(balance);

// Getting the length of the number as a string
console.log(balance.toString().length);

// Rounding the number to a fixed decimal point
console.log(balance.toFixed(1));
```

### Precision of a Number

```javascript
const otherNumber = 123.8966;
console.log(otherNumber.toPrecision(4));
```

### Formatting Large Numbers

```javascript
const hundreds = 1000000;
console.log(hundreds.toLocaleString('en-IN'));
```

### Maths Operations

```javascript
// Accessing the Math object
console.log(Math);

// Finding the absolute value of a number
console.log(Math.abs(-4));

// Rounding a number to the nearest integer
console.log(Math.round(4.6));

// Rounding up a number to the nearest integer
console.log(Math.ceil(4.2));

// Rounding down a number to the nearest integer
console.log(Math.floor(4.9));

// Finding the minimum and maximum of a set of numbers
console.log(Math.min(4, 3, 6, 8));
console.log(Math.max(4, 3, 6, 8));
```

### Random Number Generation

```javascript
// Generating a random decimal between 0 and 1
console.log(Math.random());

// Generating a random decimal between 1 and 11
console.log((Math.random() * 10) + 1);

// Generating a random integer between 1 and 10
console.log(Math.floor(Math.random() * 10) + 1);

// Generating a random integer within a specified range (min to max)
const min = 10;
const max = 20;
console.log(Math.floor(Math.random() * (max - min + 1)) + min);
```

_Understanding number operations and the Math object is crucial for performing calculations and generating random numbers in JavaScript. Use these features to handle numerical data effectively in your code._
