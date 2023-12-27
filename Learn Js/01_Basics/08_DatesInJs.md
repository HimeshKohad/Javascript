# 8. DatasInJavascript.js

In today's learning, we explore working with dates and timestamps in JavaScript.

## Dates in JavaScript

```javascript
// Creating a new Date object with the current date and time
let myDate = new Date();
console.log(myDate.toString());
console.log(myDate.toDateString());
console.log(myDate.toLocaleString());
console.log(typeof myDate);

// Creating a new Date object with a specific date and time
// let myCreatedDate = new Date(2023, 0, 23);
// let myCreatedDate = new Date(2023, 0, 23, 5, 3);
// let myCreatedDate = new Date("2023-01-14");
let myCreatedDate = new Date("01-14-2023");
// console.log(myCreatedDate.toLocaleString());
```

### Timestamps and Date Methods

```javascript
// Getting the current timestamp in milliseconds
let myTimeStamp = Date.now();

// Logging timestamps and date methods
console.log(myTimeStamp);
console.log(myCreatedDate.getTime());
console.log(Math.floor(Date.now()/1000));
```

### Working with Date Objects

```javascript
// Creating a new Date object with the current date and time
let newDate = new Date();
console.log(newDate);

// Getting the current month (0-indexed, so add 1 for human-readable month)
console.log(newDate.getMonth() + 1);

// Getting the day of the week (0-indexed, starting from Sunday)
console.log(newDate.getDay());
```

### Custom Date Formatting

```javascript
// Getting the full name of the weekday using toLocaleString
newDate.toLocaleString('default', {
    weekday: "long",
});
```

_Understanding how to work with dates and timestamps is essential for handling time-related operations in JavaScript. 
Use these features to manipulate and format dates effectively in your code._
