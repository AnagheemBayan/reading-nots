# EXECUTION CONTEXT :

* Every statement in a script lives in one of three execution contexts: 

1. global context : is not inside any function Code that is in the script

1. function context :run within a function Each function has its own function context
 
1. Eval context (not showen):Text is executed like code in an internal function called eva l ()) 

# The stack: Javascript interperter processes one line of a code at a time ,when the code have a function it stacks the function and then complete the code .

* execution context two phases of activity: 
1. prepare 

1. execute

* UNDERSTANDING ERRORS:
If a JavaScript statement generates an error, then it throws an exception.
At that point, the interpreter stops and looks for exception-handl ing code.

![err](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQABz95BtAeQtEp6p7HV7FDLn-DJAa_5dFBdw&usqp=CAU)

* ERROR OBJECTS:
1. Syntax Error
* SYNTAX IS NOT CORRECT
1. Ref erenceError
* VARIABLE DOES NOT EXIST 

1. Eval Error
* INCORRECT USE OF eval() FUNCTION

1. URI Error
* INCORRECT USE OF URI FUNCTIONS

1. Type Error 
* VALUE IS UNEXPECTED DATA TYPE

1. RangeError
* NUMBER OUTSIDE OF RANGE

1. Error
* GENERIC ERROR OBJECT

1. NaN
* NOT AN ERROR

* If you know that you may get an error, you can handle it gracefully using the try, catch, finally statements.
Use them to give your users helpful feedback. 


![error](http://gemal.dk/mozilla/pics/mozdev02.png)



