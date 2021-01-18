# Day 24
## __1/14/2021__

## What is a virtual property?
Virtual properties are properties which can take in the data present in a document and manipulate it before returning to us. This functionality is similar to GET operations on JavaScript models. 

## When might you use a virtual property?
Virtual properties are commonly useful for displaying data; one might concatenate bits of data into a more readable format. 

## How do you search by a virtual properties value?
It is not possible to query a database by a virtual property. A virtual property only exists in the mongoose schema; the Mongo database is unaware of virtual properties and cannot make use of them.
