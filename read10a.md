**Error Handling & Debugging:**

if you got many mistakes in your javascript code ,and you cant find the errors in the codes ?! then we will help you just continue reading , dont worry dont expect to write the code perfectly from the first time .

**how to find the source of an error ?**

order of execution it helps to know how scripts are processed.the order in which statements are executed can be complex.
The stack :
javascript interpreter processes one line of code at a time ,when statement needs data from another function , it stacks the new function on top of the current task.
each time a new item is added to the stack , it creates a new execution context.

**execution context and hoisting :**

there are two phases of activity , its helo you to understanding the hoisting concept ;
1. prepare :
- new scope is creatted.
- variables ,functions and arguments are created.
- the value of this keyword is determined.
2. Execute :
- it can assign values to variables.
- reference function and run the codes .
- execute statements.
understanding scope is a must , each execution context has its own variables object, it holds the variables ,function and parameters available within it .
Functions in JavaScript are have lexical scope,they are linked to the object they were defined within.

how to deal with errors ??
1- Debug the script to fix errors ;  
its deduction eliminating potential causes of an error.
you should know  where is the problem?and what exactly is the problem?
1. Look at the error message.
2. check how far the script is running .
3.  use breakpoints wher things are going wrong .
- Handle errors gracefully ;
1. when you have set breakpoints, you can see if the variables around them have the values you would expect thm to . if not , look earlier in the script.
2. break down or break out parts of the code to test smaller pieces of the functionality.

![error](https://apkvision.com/wp-content/uploads/2020/01/English-Sentence-Error-Finding.png)