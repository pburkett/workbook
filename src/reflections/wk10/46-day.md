# Day 46
## __2/22/2021__

## What are the three categories of data types? How are they different?
The three categories of data types in C# are Value, Reference, and Pointer types. Value and reference types are very similar to javascript; value types hold the value directly in memory, and are used for more simple data types. Reference types are used for more complex forms of data, and they hold a reference to the value, not the value itself. Pointers are data types used for storing memory addresses.

## What are the Value-type data types? What differences do you notice from JavaScript?
C# has quite a few value types. They are broken into 4 categories: Int number types, floating-point number types, bools, and chars. The main differences from JavaScript are the numbers; we no longer have a single Number type, we instead have many ways to represent numbers.

## In your own words how do Reference types get stored in memory? How does this differ from Value types?
Reference types get stored in memory as a reference to another location. The variable you assign a reference type to actually holds a location in memory, instead of the actual value. Ths memory location is just a middle-man between the variable and the actual data behind it.