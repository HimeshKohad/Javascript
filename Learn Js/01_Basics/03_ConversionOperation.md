# Day 3: Basics/ConversionOperation.js

In today's learning, we explore conversion operations and various mathematical and string operations in JavaScript.

## Conversion Operations

### Converting Strings to Numbers

```javascript
let score = "33abc";
console.log(typeof(score)); // Output: string

let valueInNumber = Number(score);
console.log(typeof(valueInNumber)); // Output: number (converts the type to a number, even if it's not a valid number)
console.log(valueInNumber); // Output: NaN (since "33abc" is not a valid number)
```

***Conversion to Number Rules:***
- "33" => 33
- "33abc" => NaN
- null => 0
- true => 1

### Converting Numbers to Booleans

```javascript
let isLoggedIn = 1;

let booleanIsLoggedIn = Boolean(isLoggedIn);
console.log(booleanIsLoggedIn); // Output: true
```

_**Conversion to Boolean Rules:**_
- 1 => true**
- 0 => false
- "" => false
- "hello" => true

## Mathematical and String Operations
### Mathematical Operations

```javascript
let value = 3;
let negValue = -value;
console.log(negValue); // Output: -3

console.log(2 + 2);
console.log(2 - 2);
console.log(2 * 2);
console.log(2 ** 3);
console.log(2 / 3);
console.log(2 % 3);
```

### String Concatenation

```javascript
let str1 = "hello";
let str2 = " hitesh";

let str3 = str1 + str2;
console.log(str3);

console.log("1" + 2); // Output: "12"
console.log(1 + "2"); // Output: "12"
console.log("1" + 2 + 2); // Output: "122"
console.log(1 + 2 + "2"); // Output: "32"
```

### Complex Operations

```javascript
console.log((3 + 4) * 5 % 3); // Output: 2
```

### Unary Operations

```javascript
console.log(+true); // Output: 1
console.log(+ ""); // Output: 0
```

### Chained Assignments and Increment Operator

```javascript
let num1, num2, num3;

num1 = num2 = num3 = 2 + 2;

let counter = 100;
++counter;
console.log(counter); // Output: 101
```

<hr>

## Additional Resources
For further study on type conversion, refer to the [official documentation](https://tc39.es/ecma262/multipage/abstract-operations.html#sec-type-conversion).

_Understanding these operations is crucial for effective manipulation of data in JavaScript._
