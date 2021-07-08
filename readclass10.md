**Understanding the JavaScript Call Stack**
What is a ‘call’?
a call stack is a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).

How many ‘calls’ can happen at once?
 Since the call stack is single, function(s) execution, is done, one at a time, from top to bottom. It means the call stack is synchronous.

What does LIFO mean?
its means  it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.

Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

function firstFunction(){
  console.log("Hello from firstFunction");
}

function secondFunction(){
  firstFunction();
  console.log("The end from secondFunction");
}

secondFunction();

What causes a Stack Overflow?
 when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.


 **JavaScript error messages**

 What is a ‘refrence error’?
  when you try to use a variable that is not yet declared you get this type of errors.

What is a ‘syntax error’?
this occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.

What is a ‘range error’?
when you manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.

What is a ‘tyep error’?
this types of errors show up when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.

What is a breakpoint?
be achieved by putting a debugger statement in your code in the line you want to break

What does the word ‘debugger’ do in your code?
The breakpoint can also be achieved by putting a debugger statement in your code in the line you want to break.