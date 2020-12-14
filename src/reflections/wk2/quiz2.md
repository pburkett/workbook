# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
In javaScript, the keywords 'let', 'var' and 'const' can all be used to declare a variable. Each term has it's own consequences related to scope.
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
A function is simply a repeatable chunk of code. They have to ability to take in arguments and use them internally as parameters. Functions are often designed to return some sort of information to whatever line of code invokes them.
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
The SOLID principles are intended to apply specifically to object-oriented programming. They are:
-Single-responsibility
-Open–closed
-Liskov substitution
-Interface segregation
-Dependency inversion
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
The string 'pineapple' is currently at index 2. In JavaScript,  we start at 0 when counting items in arrays.
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
The folowing code will add the 'them' object to the 'friends' array:

you['friends'].push(them)
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
(10 == 5 + 15)
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
The piece of code in the empty space is called an "incrementer", or sometimes an "update step". It is the piece of code that changes the iterator (in this case, i) that controls the repitition of the for loop. All the following pieces of code do the same thing, and  would all function in this location:
i = i + i
i += 1
i++
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
The DOM is the Document Object Model. The rendering of the DOM starts with the HTML document.
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
-undefined
-boolean
-number
-string
-bigint
-symbol
-object
-function
-null
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
The terms 'parameters' and 'arguments' describe similar things, but in different places in code. When a function is defined, it can optionally have parameters defined for use throughout the function. When a function is invoked, it can optionally have arguments attached. If the number of parameters do not match the number of arguments, the function call will, by default, fail and throw an error.
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
A primitive data type is stored by value, while a reference data type is stored by reference. The most important consequence of this is that variables that hold identical, but seperate reference data types cannot be compared meaningfully. When working with primitive data types, we get the following, predictable comparison:

var number = 30;
var numberTwo = 30;

alert(number === numberTwo); // true

But when working with reference data types, we cannot make this kind of comparison. If we set up a similar comparison, we get a different result:

var objectOne = [30];
var objectTwo = [30];

alert(objectOne === objectTwo); // false

Because reference values are stored by reference, they are always stored in different locations upon declaration. If we want a meaningful comparison of data in this case, we need to compare the primitive data types within the reference type. For example:

var objectOne = [30];
var objectTwo = [30];

alert(objectOne[0] === objectTwo[0]); // true

By using square brackets and the index of 0, we are accessing the value '30' directly, which is a primitive type. Then we are able to make a meaningful comparison.
```