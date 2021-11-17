# Expressions, Operators, and Functions

## Operators:
+ JS uses binary, unary operators, and a special ternary conditional operator
    + binary operators: requires an operator and 2 operands (values)

        i.e. operand1  operator  operand2
        + where the operator is between the two operands
    + unary operator: requires only one operator and the operand is either before or after the operator

        i.e. operand  operator or operator operand

## Expressions:
+ Expressions are any valid unit of code that resolves a value

## Functions: 
+ fundamental building blocks in JS
+ similar to a procedure
+ takes input and returns with an output

### Defining a Function:
+ Needs to include:
    + name of function
    + paramerters in parrenthasis and separated by comma
    + JS statement that defines function enclosed in {}
    + optional `return` statement that specifies the value returned by the function

### Calling Functions:
+ performs specific actions with the indicated parameters when invoked

### Function Scope:
+ variables defined within a function can be accessed outside that function
+ a function can access functions and variables within the scope it was defined

### Control Flow:
+ order computer executes statements in script
+ code runs in order from top down
    + unless it comes across structural changes to the control flow like conditions and loops
+ important to look at program structure and how it affects order of execution because a script may contain loops, functions, and conditons