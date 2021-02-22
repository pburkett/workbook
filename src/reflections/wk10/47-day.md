# Day 47
## __2/22/2021__

## What is a List in C#?
A list is a collection of items without a set length. Lists must contain items of the same data type.

## What List methods seem like you might use them often? Why?
`.Add()` and `.Remove()` seem like very good basic functionality for lists. Lists are often used when the length is unfixed, so its natural that manipulating the lists length is a likely operation to need.

## How would you retrieve an item from a list? What method could you use?
Lists have a `.find()` method that will suit most needs related to retrieving a specific item. `FindAll()` is handy when its desired to return multiple items.