![Javascript](https://i.ibb.co/BsCTKJc/68747470733a2f2f75706c6f61642e.png)

# Understanding the JavaScript Call Stack
### What is a ‘call’?
The call stack is primarily used for function invocation (call)
### How many ‘calls’ can happen at once?
one at a time
### What does LIFO mean?
Last In, First Out:it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.
### Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
```
function firstFunction(){
  throw new Error('Stack Trace Error');
}

function secondFunction(){
  firstFunction();
}

function thirdFunction(){
  secondFunction();
}

thirdFunction();
```
### What causes a Stack Overflow?
A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.
# JavaScript error messages
### What is a ‘refrence error’?
This is as simple as when you try to use a variable that is not yet declared you get this type os errors.
### What is a ‘syntax error’?
I know it’s in the name of the errors, but like it says itself, this occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.
### What is a ‘range error’?
Try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.
### What is a ‘tyep error’?
Like the name indicates, this types of errors show up when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.
### What is a breakpoint?
breakpoint make your program stop at that point only if a condition is met, this is awesome for when you want to debug huge cycles for specific values
### What does the word ‘debugger’ do in your code?
breakpoint can be achieved by putting a debugger statement in code in the line you want to break.
## Helpful resources:
- [JavaScript error messages && debugging](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)
- [The JavaScript Call Stack](https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4/)
