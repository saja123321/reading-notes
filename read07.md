# JAVASCRIPT - FUNCTIONS
## Function declarations   
* Function in JavaScript is defined by using the function keyword, followed by 
  * A unique function name, 
  * A list of parameters (that might be empty),
  * A statement block surrounded by curly braces.

![fun](https://cdn.programiz.com/cdn/farfuture/oAZVf3IqOKOYj_aJ-IoYQvbJ2CB-B3y4HXSLXBUmYcY/mtime:1591592163/sites/tutorial2program/files/javascript-function-with-parameter.png)

 ``` 
function function_nname(parameter-list)
 { statements } 
 ```

While the *function* declaration above is syntactically a statement, functions can also be created by a function expression, it does not have to have a name. For example, the function square could have been defined as:


### Function Invocation (Calling)


The code inside the function will execute when "something" invokes (calls) the function:

+ When an event occurs (when a user clicks a button)
+ When it is invoked (called) from JavaScript code
+ Automatically (self invoked)


### Function scope

Variables defined inside a function cannot be accessed from anywhere outside the function, because the variable is defined only in the scope of the function. 
*However*, a function can access all variables and functions defined inside the scope in which it is defined.