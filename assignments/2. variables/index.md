1. In code below "Mark" is a string.  What is name?
```js
var name = "Mark";
```name is  variable name. 

2. Find the error if any
```js
  var product cost = 3.45;
  ERROR : space in variable name, it won't accept.
```

3. Write `Right or Wrong` next to the code below.

```js
  "Hello World" Right
  'Hello World" (Wrong) see its still open 
  "Hello World' wrong as well
  'Hello World' Right
```

## Write `VALID` and `INVALID` infront of the variable name defined below
```js
var man; valid 
var 1girl; invalid  var name should not start with numbers.
var woman3; valid 
var -girl; invalid should not start with - as well 
var blackDog; valid 
var 42; invalid as its starting with numbers.
var $42; valid as it accepts $ & _ as well.
var userName; valid 
var x, y, z; valid its taking three values .
var x = 5, y = 6, z = 7; valid 
var x = 5 + 10 + 2; Valid 
```

## Basic Operations

Mathematical Operations:

Solve this using mathematical operations. (+, -, *, / , etc)

```js
var amount = 2080;
// Define a new variable and store the value that is 80 less then the value of amount.
var sub_80 = amount-80;
// Define a new variable and store the value that is 200 more then the value of amount.
var add_200 = amount+200;
// Define a new variable and store the value that is 4 times the value of amount.
var mul_4  = amount*4;
// Define a new variable and store the reminder when the value of amount is  divided by 21.
var div_21 = amount%21;


Logical Operation:

Solve this using logical operations. (<, >, &&, ||)

js
var johnAge = 45;
var markAge = 35;
(johnAge > markAge) && alert ("JOHN IS OLDER") || (johnAge < markAge) && alert ("mark is older");
// Check who is younger
// Check who is older eithe John or Mark
(johnAge < markAge) && alert ("mark is older") || (johnAge > markAge) && alert ("john is older");
// Check who is younger
(johnAge < markAge) && alert ("mark is older") || (johnAge > markAge) && alert ("mark is younger");

// Check if their age is equal
(johnAge == markAge) || alert("their age is equal"); 

// Create a new variable and assign the age of john to new variable.

var john_age = johnAge;
// Check if john is equal to or greater then mark.
(john_age == markAge) && alert("equal age") || (john_age > markAge) && alert("john is greater then mark");
// Check if john is less then or equal to mark.
(john_age < markAge ) && alert ("john is less then mark") || (john_age == markAge) && alert("john is equal to mark ") || alert("john is neither less nor equal to mark");

// Calculate the average age of john and mark and assign to a new variable.
var average_age = (john_age + markAge)/2;
alert (average_age);
```