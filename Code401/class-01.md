## Array.map()
map calls a provided callbackFn function once for each element in an array, in order, and constructs a new array from the results. callbackFn is invoked only for indexes of the array which have assigned values.
## Array.reduce()
The reduce() method executes the callbackFn once for each assigned value present in the array, taking four arguments:

accumulator
currentValue
currentIndex
array
The first time the callback is called, accumulator and currentValue can be one of two values. If initialValue is provided in the call to reduce(), then accumulator will be equal to initialValue, and currentValue will be equal to the first value in the array. If no initialValue is provided, then accumulator will be equal to the first value in the array, and currentValue will be equal to the second.
## superagent()
Small progressive client-side HTTP request library, and Node.js module with the same API, supporting many high-level HTTP client features
## Promises
A Promise is a proxy for a value not necessarily known when the promise is created. It allows you to associate handlers with an asynchronous action's eventual success value or failure reason. This lets asynchronous methods return values like synchronous methods: instead of immediately returning the final value, the asynchronous method returns a promise to supply the value at some point in the future.
## Are all callback functions considered to be Asynchronous? Why or Why Not?
Simply taking a callback doesn't make a function asynchronous. There are many examples of functions that take a function argument but are not asynchronous
