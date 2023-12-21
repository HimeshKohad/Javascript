# 6. Strings.js

In today's learning, we dive into string manipulation in JavaScript.

### String Concatenation

```javascript
const name = "John";
const repoCount = 50;

// Concatenating strings using the '+' operator
console.log(name + repoCount + " Value");

// Concatenating strings using template literals
console.log(`Hello, my name is ${name} and my repo count is ${repoCount}`);
```

### String Object

```javascript
const gameName = new String('hello-world');

// Accessing individual characters and checking the prototype
console.log(gameName[0]);
console.log(gameName.__proto__);
```

### Common String Methods

```javascript
// Finding the length of the string
console.log(gameName.length);

// Converting the string to uppercase
console.log(gameName.toUpperCase());

// Accessing a character at a specific index
console.log(gameName.charAt(2));

// Finding the index of a specific character
console.log(gameName.indexOf('t'));
```

### Substring and Slice

```javascript
// Extracting a substring from the string
const newString = gameName.substring(0, 4);
console.log(newString);

// Slicing the string with negative indices
const anotherString = gameName.slice(-8, 4);
console.log(anotherString);
```

### Trimming Whitespaces

```javascript
// Adding and trimming whitespaces
const newStringOne = "   hello    ";
console.log(newStringOne);

// Trimming leading and trailing whitespaces
console.log(newStringOne.trim());
```

### String Replacement

```javascript
// Replacing a substring in the URL
const url = "https://google.com/hello%20world";
console.log(url.replace('%20', '-'));
```

### Checking Inclusion and Splitting

```javascript
// Checking if a substring is present in the URL
console.log(url.includes('hello'));

// Splitting the string into an array using a delimiter
console.log(gameName.split('-'));
```

_Understanding string manipulation methods is essential for working with textual data in JavaScript. Use these methods to efficiently process and modify strings in your code._
