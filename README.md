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
