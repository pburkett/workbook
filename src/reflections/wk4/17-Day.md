# Day 17
## __1/5/2021__

## What are the three states of a promise?
A JavaScript promise can exist in one of three states: pending, fulfilled, or rejected.

## How do promises seek to resolve the issues of callback hell?
Promises seek to solve hellish callback issues by giving us the syntax to separate concerns properly. We want one block of code to manage the flow of function calls, while those functions handle their own responsibilities.

## What is the difference between .then() and .catch()?
The keywords "then" and "catch" are both used to handle javascript promises. "then()" is used to capture the resolved status of the promise within the (), and "catch()" is used to capture the failed status. Both keywords can be followed up with code to execute upon the resolution of the promise. Which block is executed is dependent on the outcome of the promise.
