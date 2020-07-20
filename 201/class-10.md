# Read: 10 - JS Debugging

## Debugging
* Debugging is the process of finding errors
* The console helps narrow down the area in which the error is located, so you can try to find the exact error
* JavaScript has 7 different types of errors:
  * Range error is thrown when a number is outside an allowable range of values
  * Reference error is thrown when a reference made to a variable/item is broken
  * Syntax error is caught by the JS engine during parsing when we type code that the JS engine can understand
  * Type error is used to indicate an unsuccessful operation when none of the other NativeError objects are an appropriate indication of the failure cause
  * URI (Unifor Resource Indicator) error indicates that one of the global URI handling functions was used in a way that is incompatible with its definition
  * Eval error is used to identify errors when using the global eval() function
  * Internal error occurs internally in the JS engine, especially when it has too much data to handle and the stack grows way over its critical limit
* When JavaScript gives an error it also gives the line of the code where the error happened