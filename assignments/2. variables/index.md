1. In code below "Mark" is a string. What is name?

```js
var name = "Mark";
//name is variable
```


2. Find the error if any

```js
  var product cost = 3.45;
//variable name should not contain spaces.
```


3. Write `Right or Wrong` next to the code below.

```js
  "Hello World" //right
  'Hello World"  //wrong
  "Hello World' // wrong
  'Hello World' //right
```

## Write `VALID` and `INVALID` infront of the variable name defined below

```js
var man; //valid
var 1girl; // invalid
var woman3; //valid
var -girl; //invalid
var blackDog; //valid
var 42; //invalid
var $42; //valid
var userName; //valid
var x, y, z; //valid
var x = 5, y = 6, z = 7; //valid
var x = 5 + 10 + 2; //valid
var user = "Tyrion"; "Arya"; "John"; //invalid
```

## Basic Operations

Mathematical Operations:

Solve this using mathematical operations. (+, -, \*, / , etc)

```js
var amount = 2080;
// Define a new variable and store the value that is 80 less then the value of amount.
var substract=amount-80;

// Define a new variable and store the value that is 200 more then the value of amount.
var add=amount + 200;

// Define a new variable and store the value that is 4 times the value of amount.
var mul = amount * 4;
// Define a new variable and store the reminder when the value of amount is  divided by 21.
var remainder = amount % 21;
```

## var, let and const

Write down the code or if there is any error write down the error.

```js
var user = "Sameer";
// Reassign the value of user to "Sam"
// Define a variable with name user with value "Irfan"
user = "Sam";
var user = "Irfan";

let number = 21;
// Reassign the value of number to 60
// Define another variable called number with the value of 100
number = 60;
 let number = 100;



const username = "Admin";
// Reassign the value of username to "Arya"
// Define a variable called usernae with value "John"
username = "Arya";
const username = "John";
```

Logical Operation:

Solve this using logical operations. (<, >, &&, ||)

```js
var johnAge = 45;
var markAge = 35;

// Check who is older eithe John or Mark
if(johnAge>markAge){
  console.log(johnAge);
}
// Check who is younger
else{
  console.log(markAge);
}

// Check if their age is equal
if(j)
// Create a new variable and assign the age of john to new variable.
var ageJohn=johnAge;
// Check if john is equal to or greater then mark.
alert(ageJohn == markAge);
// Check if john is less then or equal to mark.
alert(ageJohn<= markAge);

// Calculate the average age of john and mark and assign to a new variable.
var avg=(ageJohn+markAge)/2;
```

Output of the following and why :

```js
let charactor = "Arya";
charactor = "John";
console.log(typeof charactor);
//string
```

Output of the following and why :

```js
let charactor = "Arya";
console.log(typeof charactor);
charactor = 10;

//string 10
```

valid or not (why)

```js
null = 10;
console.log(null);

//null is pr
//Uncaught SyntaxError: Invalid left-hand side in assignment
```
