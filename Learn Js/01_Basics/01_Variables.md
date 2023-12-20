# Day 1: Variables.js

Today's learning includes understanding the basics of variables in JavaScript. Let's explore the key concepts through the provided JavaScript file.

## Constants

Constants are declared using `const` and cannot be changed once assigned.

```javascript
const accountId = 1234455; // Constant value - cannot be changed
```

## Variables
There are two ways to declare variables in JavaScript: let and var.

```javascript
let accountEmail = "hello@google.com";
var accountPassword = "12345";
```

### Memory Reservation (Avoid This)
It is possible to reserve space in memory without declaring the variable type. However, it is considered bad practice, and it's recommended not to use this approach.

```javascript
accountCity = "Mumbai"; // Reserving space in memory (avoid this)
```

### Undefined Variables
If a variable is declared without initializing it, it will be undefined.

```javascript
let accountState; // Undefined variable
```

### Changing Values
Values of variables can be changed after declaration, except for constants.

```javascript
accountEmail = "hi@google.com";
accountPassword = "21212121";
accountCity = "Delhi";
```

### Logging Values
Use console.log() to display values in the console.

```javascript
console.log(accountId); // Output: 1234455
```

### Table Display
console.table() can be used to display values in a tabular format.

```javascript
console.table([accountId, accountEmail, accountPassword, accountCity, accountState]);
```

<hr>

## Best Practices
- Prefer using const for constants.
- Use let for variables that need to be reassigned.
- Avoid using var due to issues with block scope and functional scope.

_Remember to follow best practices for variable declarations to write clean and maintainable code._
