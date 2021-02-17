# Error Handling & Debugging

## What is Debugging

![ ](https://image.slidesharecdn.com/debugging-javascript-web-141030080414-conversion-gate02/95/debugging-javascript-1-638.jpg?cb=1415345877)

> Debugging is a process for testing, finding the errors and reducing them from happening in future.
> Debugging JavaScript either requires having support for JavaScript debugger
> keyword, breakpoint support with web browser tools, or third-party tools.
> These tools range from browser plugins like Augury which is an Angular development and debugging
> extension for Chrome, third-party tools & more. It is also possible to use ‘debugger’ keyword support
> (depending on the browser type and version) and to freeze the code at a >given point and investigate the issue.
> Let us look at few popular debugging and error handling tools.

## Why errors happened ?

> ***some times the excution order can be the reason to have an error, because some asks cannot complete until another statement or function has been run in a certain order.***
> ***JavaScript can be hard to learn and everyone makes mistakes when writing it.***
> ***Error Handling & Debugging will help you learn how to find the errors in your code.***
> ***It will also teach you how to write scripts that deal with potential errors gracefully.***
> *When you are writing JavaScript, do not expect to write it perfectly the first time. Programming is like problem solving: you are given a puzzle and not only do you have to solve it, but you also need to create the instructions that allow the computer to solve it. too.*

*When writing a long script, nobody gets everything right in their first attempt. The error messages that a browser gives look cryptic at first, but they can help you determine what went wrong in your JavaScript and how to fix it.*

## ORDER OF EXECUTION

***To find the source of an error, it helps to know how scripts are processed. The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run.***

![ ](https://blog.jetbrains.com/wp-content/uploads/2017/09/webstorm-debug-local.gif)

* The greeting variable gets its value from the greetUser() function.
* greetUser() creates the message by combining the string 'He 11 o ' with the result of getName ().
* getName () returns the name to greetUser() .
* greetUser() now knows the name, and combines it with the string. It then returns the message to the statement that ca lled it in step 1.
* The value of the greeting is stored in memory.
* This greeting variable is written to an alert box.

***There are 3 types of errors in programming:***

* Syntax Errors : Occur at compile time in traditional programming languages and at interpretation time in JavaScript.
* Run time Error : Also called exceptions, occur during execution (after compilation/interpretation).
* Logical Error : Logic errors can be the most difficult type of errors to track down.

Exception Handling:
Exception handling is accomplished with a try…catch statement. When the program encounters an exception, the program will terminate in an unfriendly fashion. To safeguard against this unanticipated error, we can wrap our code in a try…catch statement.

* There are seven types of built-in error objects in JavaScript.
***SyntaxError***
*SYNTAX IS NOT CORRECT :* This is caused by incorrect use of the rules of the language. It is often the result of a simple typo.
***ReferenceError***
*VARIABLE DOES NOT EXIST :* This is caused by a variable that is not declared or is out of scope.
***EvalError***
*INCORRECT USE OF eval() FUNCTION The eval ()* function evaluates text through the interpreter and runs it as code. It is rare that you would see this type of error, as browsers often throw other errors when they are supposed to throw an Eva 1 Error.
***URIError***
*INCORRECT USE OF URI FUNCTIONS :* If these characters are not escaped in URls, they will cause an error: / ? & I : ;
***TypeError***
*VALUE IS UNEXPECTED DATA TYPE :* This is often caused by trying to use an object or method that does not exist.
***RangeError***
*NUMBER OUTSIDE OF RANGE :* If you call a function using numbers outside of its accepted range.
***Error***
*GENERIC ERROR OBJECT :* The generic Error object is the template (or prototype) from which all other error objects are created.

## The Stack

*The JavaScript interpreter processes one line of code at a time. when a statement needs data from another function it stacks the new function on top of the current task.*

## EXECUTION CONTEXT & HOISTING

*Each time a script enters a new execution context, there are two phases of activity:*

## HANDLING EXCEPTIONS

*If you know your code might fail, use try, catch, and finally. Each one is given its own code block.*

~~~
   try {
       // Try to execute this code
               
   }catch (exception) {
       // If there is an exception, run this code
               
   }finally {
       // This always gets executed
   }
~~~

### SUMMARY debuging

> * In JavaScript,the interpeter uses the concept of execution contexts, like function contexts gets executed without being the first in order.
> * JS Interpeter processes one line of code at a time,when something requires data from another function it stacks (piles) the new function on top of the current task
> * Scope is like a container for variables if the variable isnt a global variable.
> * When a statement gives an error then it throws an exception and the interpeter stops and looks for exception handling code.
> * Error objects are created to help you find the mistakes in your code.
> * Types of errors: 1-Syntax error 2- mismatching or unclosed quotes 3-missing closing bracket, etc...
> * Deal with errors: debug the script, or by using try,catch,throw and finally statements, like when you request data from third party site and their server doesn't respond.
> * Different browsers have different styles of consoles.
> * You can try your code in the browser's console directly.
> * Always log data to console to find what happenss
