# Day 7
__12/08/2020__

## What are the three syntactic means of defining a function?
    -Function Declaration (the normal way)
        -comes with a name
        -Hoisted!
    -Function Expression
        -Anonymous (no name)
        -Can be saved to a variable
        -Un-hoisted
    -Arrow Function Expression
        -Does not create a 'this' value (not that I know what that means, yet...)
        -Has traits of typical function expressions

## What is the difference between arguments and parameters?
    Both terms are used to describe the data that functions use, but arguments are external while parameters are internal. In other words, when defining a function, we use parameters. When invoking a function, we use arguments.

## What are higher order functions?
    In JavaScript, we can use functions as arguments for other functions. A typical example of this is Array.prototype.find()