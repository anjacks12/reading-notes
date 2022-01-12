# Reading 10: Debugging

Resources: Notes were made from Jon Duckett's JavaScript & jQuery book (see Resources)

## Chapter 10: Error Handling & Debugging

* The Stack:
  * JS interpreter reads code one line at a time
    * if multiple functions are needed to run the initially called function, JS puts the that function and the preceding functions until the function that triggers the subsequent function is called

* Error Objects helps find errors
  * Errors have name, message, fileNumber, and line number
    * these errors help in locating errors that may be found in the script/code
  * There are 7 built in error objects:
    * `Error`
    * `SyntaxError`
    * `RefrenceError`
    * `TypeError`
    * `RangeError`
    * `URIError`
    * `EvalError`
* How to deal with errors
  * Debug script to fix errors:
    * This is done by tacking down script and syntax errors using developer tools
  * Handle errors gracefully
    * Can use `try`, `catch`, `throw`, and `finally` if you think the code might fail
      * This is used for errors that may occur outside of the code (i.e. the use of a particular browser or server issues)