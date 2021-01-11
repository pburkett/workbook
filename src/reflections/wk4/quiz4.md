# UnderStanding Asynchronous Code, and API's

**1.** What is the difference between `asynchronous` code and `synchronous` code?
<!-- enter you answer in the space below -->
```
**Synchronous code executes in a predictable order**, and is contained within the browser. By saying it executes in a predictable order, I mean that you could predict the exact order your code wil be executed in response to specified actions by the user. For example, you know the exact path an event will take. A button will execute a function in your controller, which will route to your service, which will make a change to your data, which will trigger a draw function in your controller. If the user were to click another button before the first one was finished executing, JavaScript would wait until it had finished the first button's many code blocks before executing any code from the second button. **Asynchronous code does** ***not*** execute in a predictable order**, and does not have to be contained within the browser. Asynchronous code is most often used to communicate with entities outside of your browser, such as API's. Since these entities are outside of your browser, JavaScript cannot know when they will finish communicating with you, or if they will even respond. Because of this, we need to write code that can handle unpredictable behavior. If an API takes several seconds to respond, a fully synchronous program would leave the user waiting for tasks that could be completed in the meantime.
```
**2.** What is an event listener?
<!-- enter you answer in the space below -->
```
An event listener is named quite literally; an event listener listens for events. Event listeners allow us to execute code when certain actions take place. This concept can be used both in the DOM and within pure JavaScript. For example, we can create an event listener that applies a CSS animation when the user hovers over an element. We can also make a different kind of event listener that triggers functions when set operations are used on data. (This second example is also an observer.)
```
**3.** What does the `O` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
The Open-Closed principle says that software should be *open* for extension, but *closed* for modification. Following this principle ahs brought us much of the wonderful open source code in the world. In practice, there is plenty of software in the world that is closed for both extension and modification. 
```
**4.** What is a callback / higher order function?
<!-- enter you answer in the space below -->
```
A simple definition of a higher order function is one that takes in another function as an argument. In practice, we often use higher order functions to encapsulate asynchronous code, i.e., code that will make a request outside of the browser. A higher order function essentially says to JavaScript "do X, and when you're done, use the output of X to do Y".
```
**5.** What is a `promise`? How do you capture an error from a `promise`?
<!-- enter you answer in the space below -->
```
A JavaScript promise is another way to approach aysnchronous code. A promise is an object that will produce either a single value, or an error desribing why the requested value was not returned. They can be in one of 3 states: pending, fulfilled, and rejected. The `.catch()` can be used to capture errors from promises.
```
**6.** Name three processes used to make requests over `HTTP`?
<!-- enter you answer in the space below -->
```
The 3 most import processes for requests over `HTTP` are get, post, and delete. Their names are fairly self-evident; get allows you to retrieve a collection by URL, post allows you to create a new object within a collection, and delete allows you to remove a single object by providing it's ID.
```
**7.** What does the `API` acronym stand for?
<!-- enter you answer in the space below -->
```
API stands for Application Programming Interface. It is essentially a method for one application to communicate with another.
```
**8.** In the `MVC` design pattern, who is responsible for making calls to `APIs`?
<!-- enter you answer in the space below -->
```
In an MVC pattern, the service is responsible for handling data manipulation. Making calls to `APIs` is part of that responsibility.
```
**9.** What is the purpose of encapsulation in programming?
<!-- enter you answer in the space below -->
```
Encapsulation is a basic way to hide data. It prevents access one portion of code from accessing all the rest of it. It also keeps data away from users.
```
**10.** What is `HTTP` response code for a successful request?
<!-- enter you answer in the space below -->
```
Reponse code `200` represents a successful request.
```
**11.** What is a 500 error?
<!-- enter you answer in the space below -->
```
A 500 error represents a generic internal server error. It means that the server was unable to serve your request, and didn't provide any information as to why.
```