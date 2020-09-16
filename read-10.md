# ERROR HANDLING & DEBUGGING

THE STACK


The JavaScript interpreter processes one line of code at a time . When a statement needs data from 
another function, it stacks (or piles) the new function on top of the current task.


When a statement has lo cal\ some other code i n order to do its job, the new task goes to the top 
of the pile of things to do.

Once the new task has been performed, the interpreter can go back to the task in hand.

Each time a new item is added to the stack, it creates a new execution context.

Variables defined in a function (or execution context) are only available in that function.

II a function gets called a second time, the variables can have different values.
![java](/img/func.png)  

![java](/img/java.png)  ![java](/img/java2.png)  

## EXECUTION CONTEXT & HOISTING

Each time a script enters a new execution context, there are two phases
of activity:

### PREPARE:
* The new scope is created
* Variables, functions, and arguments are created
* The value of the this keyword is determined

### EXECUTE:
* Now it can assign values to variables
* Reference functions and run their code
* Execute statements

## UNDERSTANDING SCOPE

In the interpreter, each execution context has its own va ri ables object.
It holds the variables, functions, and parameters available within it.
Each execution context can also access its parent's v a ri ables object.

![scope](/img/funcbic.png)  

## ERROR OBJECTS 

Error objects can help you find where your mistakes are and browsers have tools to help you read them.

## ERROR OBJECTS CONTINUED

1- Syntax Error :
- SYNTAX IS NOT CORRECT
This is caused by incorrect use of the rules of the
language. It is often the result of a simple typo.

2- Ref erenceError :
- VARIABLE DOES NOT EXIST
This is caused by a variable that is not declared or is out of scope.

3- EvalError :
- INCORRECT USE OF eval() FUNCTION
The eva l () function evaluates text through the
interpreter and runs it as code (it is not discussed
in this book). It is rare that you would see this type of error, as browsers often throw other errors when they are supposed to throw an Eva 1 Error.

4- URI Error :
- INCORRECT USE OF URI FUNCTIONS
If these characters are not escaped in URls, they will cause an error: / ? & I : ;

5- Type Error
- VALUE IS UNEXPECTED DATA TYPE
This is often caused by trying to use an object or
method that does not exist.

6- RangeError
- NUMBER OUTSIDE OF RANGE
If you call a function using numbers outside of its
accepted range.

## HOW TO DEAL WITH ERRORS :

1 - DEBUG THE SCRIPT TO FIX ERRORS:
If you come across an error while writing a script
(or when someone reports a bug), you will need to
debug the code, track down the source of the error,
and fix it.


2 - HANDLE ERRORS GRACEFULLY: 
You can handle errors gracefully using try, catch,
throw, and f i na 1 ly statements.

## BROWSER DEV TOOLS & JAVASCRIPT CONSOLE:

* The JavaScript console will tell you when there is a problem with a script, where to look for the problem, and what kind of issue it seems to be.

## BREAKPOINTS:
You can pause the execution of a script on any
line using breakpoints. Then you can check the
va lues stored in variables at that point in time.

![breakpoints](/img/stop.png) 

## DEBUGGER KEYWORD:
You can create a breakpoint
in your code using just the
debugger keyword. When the
developer tools are open, this
will automatically create a
breakpoint.
![breakpoints](/img/debugg.png) 
