# simon
first repository

/......................\
#JavaScript Variable
JavaScript Local variable
JavaScript Global variable
A JavaScript variable is simply a name of storage location. There are two types of variables in JavaScript : local variable and global variable.

There are some rules while declaring a JavaScript variable (also known as identifiers).

Name must start with a letter (a to z or A to Z), underscore( _ ), or dollar( $ ) sign.
After first letter we can use digits (0 to 9), for example value1.
JavaScript variables are case sensitive, for example x and X are different variables.

Example of JavaScript variable

<script>  
var x = 10;  
var y = 20;  
var z=x+y;  
document.write(z);  
</script>  
\...........................\

#Javascript Data Types
JavaScript provides different data types to hold different types of values. There are two types of data types in JavaScript.

Primitive data type
Non-primitive (reference) data type
JavaScript is a dynamic type language, means you don't need to specify type of the variable because it is dynamically used by JavaScript engine. You need to use var here to specify the data type. It can hold any type of values such as numbers, strings etc.

JavaScript primitive data types
There are five types of primitive data types in JavaScript. They are as follows:

Data Type...........	Description
String	.............represents sequence of characters e.g. "hello"
Number	..............represents numeric values e.g. 100
Boolean	...............represents boolean value either false or true
Undefined	..............represents undefined value
Null	...................represents null i.e. no value at all


#JavaScript non-primitive data types
The non-primitive data types are as follows:

Data Type	..............Description
Object	................represents instance through which we can access members
Array	...................represents group of similar values
RegExp	.................represents regular expression

\.....................................................................................\

JavaScript continue statement
There is full control to handle loop statements in JavaScript. Sometimes, a situation occurs when we require to skip some code of the loop and move to the next iteration. It can be achieved by using JavaScript's continue statement.

The continue statement in JavaScript is used to jumps over an iteration of the loop. Unlike the break statement, the continue statement breaks the current iteration and continues the execution of next iteration of the loop. It can be used in for loop, while loop, and do-while loop. When it is used in a while loop, then it jumps back to the condition. If it is used in for loop, the flow moves to the update expression.

When we apply the continue statement, the program's flow immediately moves to the conditional expression, and if the condition is true, then the next iteration will be started; otherwise, the control exits the loop.
