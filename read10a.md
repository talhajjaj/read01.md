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