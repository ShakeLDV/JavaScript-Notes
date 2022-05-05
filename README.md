# JavaScript-Notes

Just a collection of JavaScript Notes.

Big note everytime you start going through these notes. The code always has to end in ; or it isn't going to run.


making a variable
```
var myName = "Leighiam";
```

to prompt a user to type something
```
prompt("What is your name?");
```
To store that inside a variable
```
var yourName = prompt("What is your name?");
```
Combining variables with string (I wish this had f strings)
```
alert("My name is" + myName + ", welcome to my github" + yourName + "!");
```
Printing to the console is not print() in JavaScript. It is as follows
```
console.log("Hello peeps");
```
## Strings
(I'm missing fstrings already)
```
"a" + "b" + "c";

"Hello" + " " + "World!";

var yourName = prompt("Input your name");

console.log("Hello there! " + yourName);

```

### String lengths

```
var name = "Leighiam";
name.length;
```
#### Exercise 1
```
var userMessage = prompt("What is your message?);
var lengthMessage = userMessage.length;
var requiredLength = 140

console.log("You have written" + lengthMessage + "characters, you have" + (requiredLength - lengthMessage) + "characters left.")
```
#### String Slicing
```
var name = "Leighiam";
name.slice(0,1);
//output is "L"

if its added more.

name.slice(0,4);
//output is "Leigh"
```

#### Exercise 2
```
var userMessage = prompt("What is your message?);
var slicedMessage = userMessage.slice(0,140);

console.log(slicedMessage);

or

var userMessage = prompt("What is your message?);
console.log(userMessage.slice(0,140);
```

#### toUpperCase() and to LowerCase() function

```
var myName = "leighiam";
myName = myName.toUpperCase();
myName = myName.toLowerCase();

//output is leighiam
```

## Numbers

### Increment & Decrement

```
var x = 5;   | var x = 5;
x = x + 1;   | x = x - 1;

or 

var x = 5;   | var x = 5;
x ++;        | x --;
```
Adding two variable 
```
x += y
```

## Functions
Making a function
```
function getMilk(){
  Whatever code is inside the function
  }
```
To call the function
```
getMilk();
```
Adding an input to the function
```
function getMilk(bottles){
  var money = 20
  var cost = 1.5
  Whatever code is in the function + 
  var change = Math.floor(Bottles * cost)
}
getMilk(5)
```
## Random Function

Exercise: Love Calculator
```
prompt("What is your name?");
prompt("What is your loves name?");
var n = Math.random() * 100;
n = Math.floor(n) + 1;
console.log("You two match are a match of this much: " + n);
```
## Conditionals

Exercise: Love Calculator but with Conditionals
```
prompt("What is your name?");
prompt("What is your loves name?");
var n = Math.random() * 100;
n = Math.floor(n) + 1;
if (n === 100){
    alert("Your love score is " + n + "%" + " You love each other like Kanye loves Kanye.");
}else {console.log("You two match are a match of this much: " + n + "%");
}

```
Comparators and Equality
```
=== Is equal to
!== Is not equal to
> Is greater than
< Is lesser than
>= Is greater or equal to
<= Is lesser or equal to
```
Combining Comparators
```
&& AND
|| OR
! NOT
```
Exercise: Love Calculator but with conditional comparators (much different than Pythons elif)
```
if (n === 100){
    alert("Your love score is " + n + "%" + " You love each other like Kanye loves Kanye.");
}
if (n > 70){
  alert("Your love score is " + n + "%" + "You love each other like Kanye love Kim);
}
if (n > 30 && n <= 70){
  alert("Your love score is " + n + "%");
}
if (n <= 30){
  alert("Your love score is " + n + "%" + "You go together like oul and water.");
} else {console.log("You two match are a match of this much: " + n + "%");
}
```
## Arrays
Example Array
```
var eggs = [blue egg, white egg, yellow egg, red egg];

To get something from the array
var egg = eggs[0];

To count how much is inside the array
eggs.length;

To check to see if something is inside of an array
eggs.includes(yellow egg)
//output True (boolean)
```

## Loops

### While Loop
```
var i = 1;

while (i<2) {
  console.log(i);
  i++;
}
```

### For Loop
```
for (var i = 0; i<2; i++){
  console.log(i);
}
```

### API

Application Programming Interfaces

An Application Programming Interface (API) is a set of commands, functions, protocols, and objects that programmers can use to create software or interact with an external system.
