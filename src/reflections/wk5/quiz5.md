# Intro to Server side concerns with JavaScript

**1.** What do the letters of the acronym `CRUD` stand for?
<!-- enter you answer in the space below -->
```
CRUD stands for create, read, update, and delete.
```
**2.** Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?
<!-- enter you answer in the space below -->
```
Each CRUD action corresponds to an HTTP request as follows:
Create - Post
Read - Get
Update - Put
Delete - Delete
```
**3.** What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB
<!-- enter you answer in the space below -->
```
ORM stands for Object Relational Mapping. When interacting with MongoDB, we use Mongoose as our ORM.
```
**4.** Which two `HTTP` request types include a body?
<!-- enter you answer in the space below -->
```
Put and Post requests both require a body. 
```
**5.** In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.
<!-- enter you answer in the space below -->
```
Object Oriented
Functional
```

**6.** Fill in the missing piece of this snippet of code.
```js
import ______ from "_______"
let Schema = ________.Schema;
```
<!-- enter you answer in the space below -->
```
mongoose
```
**7.** What is middleware?
<!-- enter you answer in the space below -->
```
Middleware is a blanket term for all software that acts between the main functionality of a server and the clients it interacts with. Middleware can be used to handle incoming HTTP requests before the API handles them.
```
**8.** The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 
<!-- enter you answer in the space below -->
```
Request
Response
```
**9.** 
Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.
<!-- enter you answer in the space below -->
```
To include query paramaters with a request, we can append `?tag=winter`. If the server is able to handle queries on the request we are making, we should be returned only resources which have a matching `tag: winter` property.
```