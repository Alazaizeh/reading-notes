![Javascript](https://i.ibb.co/BsCTKJc/68747470733a2f2f75706c6f61642e.png)

# Error Handling & Debugging

## Order Of Execution 
To find the source of an error, it helps to know how scripts are processed.
The order in which statements are executed can be complex; some tasks
cannot complete until another statement or function has been run: 

## Execution Context
Every statement in a script lives in one of three execution contexts:
1. **Global Context** Code that is in the script, but not in a function. There is only one global context in any page.
2. **Function Context** Code that is being run within a function.Each function has its own function context.
3. **Eval Context** Text is executed like code in an internal function called eval().

## EXECUTION CONTEXT & HOISTING
Each time a script enters a new execution context, there are two phases of activity:
1. PREPARE
     * The new scope is created
     * Variables, functions, and arguments are created
     * The value of the this keyword is determined
2. EXECUTE
     * Now it can assign values to variables
     * Reference functions and run their code
     * Execute statements
