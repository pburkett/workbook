# Day 12
__12/15/2020__

## What is the purpose of encapsulation?
Encapsulation allows us to nest data away from direct access by the user. This can be used to prevent unintended actions, especially at the JavaScript console accessible in dev tools. Without any encapsulation, it would typically be possible to call any function, re-assign any variable, and otherwise wreak havoc at the console. 

## What were some of the problems with closure and the underscore prefix?
The underscore prefix is conventionally used to indicate that a variable is private. However, without real enforcement though encapsulation, it's easy for the private status to be ignored entirely and for unintended consequences to arise. A good example is when creating JavaScript packages for other programmers to use. If your private variables are only private because of an underscore prefix, it's easy for programmers to disregard these and cause unintended behaviors.

## How do we create private variables in a ES6 class? Why would you do this?
We can create a private variable in an ES6 class by declaring one using 'var' in the class constructor. A variable declared this way will not be accessible to entities outside the class. The class can access the variable in all its functions, and can be coded to output the private variable via a function. 