# ERROR , HANDLING & DEBUGGING :
To find the source of an error, it helps to know how scripts are processed.
The order in which statements are executed can be complex; some tasks
cannot complete until another statement or function has been run.

The JavaScript interpreter uses the concept of execution contexts.
There is one global execution context; plus, each function creates a new
new execution context. They correspond to variable scope. 

THE STACK: the javascript interpreter processes one line of code at a time.
When a statement needs data from another function, it stacks the new function on top of current task.

Each time a script enters a new execution context, there are two phases
of activity: 
1-Prepare 
• The new scope is created
• Variables, functions, and arguments are created
• The value of the this keyword is determined 
2-Execute 
• Now it can assign values to variables
• Reference functions and run their code
• Execute statements 

Error objects can help you find where your mistakes are and browsers have tools to help you read them. 
Types of error :
Syntax Error ->This is caused by incorrect use of the rules of the language. It is often the result of a simple typo. 
ReferenceError-> This is caused by a variable that is not declared or is out of scope.
Type Error-> This is often caused by trying to use an object or method that does not exist. 
RangeError-> If you call a function using numbers outside of its accepted range. 

How to deal with errors ? 
1: DEBUG THE SCRIPT TO FIX ERRORS (debugging is about deduction)
2: HANDLE ERRORS GRACEFULLY 

Browsers that have a console have a console object, which has several
methods that your script can use to display data in the console. The object is documented in the Console API. 
You can pause the execution of a script on any line using breakpoints. Then you can check the
values stored in variables at that point in time. 

If you set multiple breakpoints, you can step through them one-by-one to see where values change and a problem might occur.
You can indicate that a breakpoint should be triggered only if a condition that you specify is met. The condition can use existing variables.
 
NOTES:If you know your code might fail, use try, catch, and finally each one is given its own code block.
      If you know something might cause a problem for your script, you can generate your own errors before the interpreter creates them.