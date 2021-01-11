# Day 16
## __1/4/2021__

## What are the signs and causes of "Callback Hell"?
Callback hell is a result of poor asynchronous code. When developers try to write async code in a top-down manner, they often find themselves in callback hell. Callback hell is very hard to read, modify, and prone to errors due to its visual complexity. Deeply nested code (chevron or pyramid shaped) is a symptom of callback hell. 

## What does aynchronous mean, and how are callbacks involved?
Asynchronous means "not at the same time". In software, it means "not in a predictable order, or not immediately after". The convention of a callback describes a function which is executed after the execution of an asynchronous function. The term callback can be interpreted as "*call* you *back* when I'm done".

## Describe three ways to fix or prevent Callback Hell.
To avoid callback hell, we should build functions that perform our different tasks, and call to those instead of placing the code directly. It can be helpful to think of one block of code managing the order or timing of many functions by calling out to them. Fortunately, using MVC gets us pretty far from callback hell already. We can split different operations between services, controllers, and models. If we still find our sequence of callbacks to be too verbose, we can connect multiple services.