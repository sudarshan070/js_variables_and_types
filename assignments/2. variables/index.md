1. In code below "Mark" is a string. What is name?

```js
var name = "Mark";
name is a variable name
```

2. Find the error if any

```js
  var product cost = 3.45;
  const is error
  var product = 3.45
```

3. Write `Right or Wrong` next to the code below.

```js
  "Hello World"  // Right
  'Hello World"  // Wrong
   "Hello World'   //Wrong
  'Hello World'  // Right
```

## Write `VALID` and `INVALID` infront of the variable name defined below

```js
var man; // valid
var 1girl;  //  variables can not start with digit
var woman3;  // valid
var -girl;    //  variables can not start with -
var blackDog;   // valid
var 42;         //  variables can not start with digit
var $42;        // valid
var userName; // valid
var x, y, z;   // valid
var x = 5, y = 6, z = 7;  // valid
var x = 5 + 10 + 2;    // valid
var user = "Tyrion"; "Arya"; "John";  // valid
```

## Basic Operations

Mathematical Operations:

Solve this using mathematical operations. (+, -, \*, / , etc)

```js
var amount = 2080;
// Define a new variable and store the value that is 80 less then the value of amount.
var newValue = 80;
var less = amount - newValue;
less;

// Define a new variable and store the value that is 200 more then the value of amount.
var more = 200;
var add = amount + add;
add;

// Define a new variable and store the value that is 4 times the value of amount.
var value = 4;
var product = amount * value;
product;

// Define a new variable and store the reminder when the value of amount is  divided by 21.
var div = 21;
var reminder = amount / div;
reminder;
```

## var, let and const

Write down the code or if there is any error write down the error.

```js
var user = "Sameer";
// Reassign the value of user to "Sam"
var user = "Sam";
// Define a variable with name user with value "Irfan"
var user = "Irfan";

let number = 21;
// Reassign the value of number to 60
let number = 60;
// Define another variable called number with the value of 100
let number = 100;

const username = "Admin";
// Reassign the value of username to "Arya"
const username = "Arya";
// Define a variable called usernae with value "John"
const username = "John";
```

Logical Operation:

Solve this using logical operations. (<, >, &&, ||)

```js
var johnAge = 45;
var markAge = 35;

// By using coditional operator
var result = condition ? value1 : value2;
// Check who is older eithe John or Mark

var older = markAge < johnAge ? "mark is older" : "john is older";
older;

// Check who is younger
var younger = markAge < johnAge ? "mark is younger" : "john is younger";
younger;
// Check if their age is equal
var equalAge = markAge == johnAge ? true : false;
equalAge;
// Create a new variable and assign the age of john to new variable.
var newAge = johnAge;
newAge;
// Check if john is equal to or greater then mark.
var equalGreater = markAge <= johnAge ? true : false;
equalGreater;
// Check if john is less then or equal to mark.
var equalLess = johnAge <= markAge ? true : false;
equalLess;

// Calculate the average age of john and mark and assign to a new variable.
var avg = (johnAge + markAge) / 2;
avg;
```
