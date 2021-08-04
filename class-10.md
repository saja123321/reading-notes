# java Script EXECUTION CONTEXTS

statments in execiuttion is one of three :

### 1. GLOBAL CONTEXT
the code in the whole script not inside functions 
.

### 1. FUNCTION CONTEXT 

the code inside function called ***function context***

### 1. EVAL CONTEXT (NOT SHOWN)
Text is executed like code in an internal function


# VARIABLE SCOPE 
### - GLOBAL SCOPE
If a variable is declared outside a function, it can
be used anywhere because it has global scope.
If you do not use the var keyword when creating
a variable, it is placed in global scope.
### - FUNCTION-LEVEL SCOPE
When a variable is declared within a function,
it can only be used within that function. This is
because it has function-level scope.

Examples 
```
let x = 10;

function timesTen(a){
    return a * 10;
}

let y = timesTen(x);

console.log(y); // 100
```

1. First, assign `10` to the `x` variable.
1. Second, declare a function `timesTen()` that multiplies its argument with `10`.
1. Third, call the `timesTen()` function by passing in `x` as a parameter and store the return value in the variable `y`.
Finally, output the variable `y` to the Console.

in the below image it desplay how the Javascrept interrubter works:

-----------------

![java](https://miro.medium.com/max/640/0*RRgTDdRfLGEhuR7U.png)

-------------------- 

# ERROR OBJECTS  

Error objects can help you find where your mistakes are
and browsers have tools to help you read them. 

the erorrs in javascript cotain some element :

PROPERTY          |     DESCRIPTION              |
------------------|------------------------------|
name              |  Type of execution           |
message           | Description                  |
file eNumber      | Name of the JavaScript file  |
line neNumber     | Line number of error         |


