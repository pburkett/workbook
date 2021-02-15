# Day 43
## __2/14/2012__

## What are the three main types of testing we can accomplish in Vue? What does each method provide?
Within the scope of Vue, we can test functions, components, and the entire API layer for single routes. These are called unit testing, component testing, and End-to-End testing respectively. Unit tests test very small portions of code, and thorough unit testing can give developers a lot of confidence in their code, and make debugging incredibly smooth. However, unit testing each function is laborious. Component testing will provide less detail than unit testing, but will also be quicker to write for the same amount of code. E2E testing tests can cover far more code, but the amount of detail when errors occur will be limited.

## What testing method do you think is the most useful? Why?
I think E2E is the most useful, as it will typically give you best code coverage:labor ratio. 

## What testing method do you think is the least useful? Why?
I think component testing will often be the least useful, as it strikes the worst balance between labor and detail. If your goal is to have a high level of detail in your tests, I think unit tests are often the best choice.