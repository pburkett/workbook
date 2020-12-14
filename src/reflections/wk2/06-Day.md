# Day 6
__12/07/2020__

## What is scope?
In  OOP, scope is used to define where in a program a variable can be accessed. By design, variables are limited to the environment they are declared in, or their scope. If a variable is declared within of function, it is only available for use within that function. If a variable is declared outside of a function, it can be available for use within all the functions within that same file.

## What is hoisting?
A "hoisted" piece of code is code that is run before the rest of the block. The most notable examples of hoisting are functions and variables declared with 'var'. It is worth noting that 'var' only hosts the declaration, not the assignment. 

## In what cases might you use let vs const vs var?
Let is a useful method for declaring variables when you have no intention of using the variable outside of the curly braces (for loop, if statement, function, etc) you are declaring the variable in. Using let will prevent you from causing bugs if you use the same variable name in different {} throughout your code. Var is a useful method when you *do* intend to use a variable outside of the scope it's being declared in. You also may find it useful to declare a variable in a broad scope, such as outside a function, and then assign it a value within the function. Const is useful when you want to prevent the re-assignment of a variable, as variables declared with const and considered "constants", and they cannot be changed.