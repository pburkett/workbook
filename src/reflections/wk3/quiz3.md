# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```

```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->
```
staff[property]
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
The generic definition of encapsulation is "the action of enclosing something in or as if in a capsule". In software, we use encapsulation to describe when we enclose data to prevent direct access by the user. In this context, data can refer to variables, functions, classes, or any other JavaScript data type. So far, we have accomplished encapsulation through organizung our code into a file structure, the pattern for which we dictate using MVC. However, encapsulation can be accomplished by other means as well.
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
The 'S' in SOLID stands for "single responsibility principle". This means that a class should have only one job, or responsibility, and therefore only one reason to be changed. for example, one class should be repsonsible for formatting data, and another should be responsible for performing calculations.
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
A class is simply a blueprint with which you can create instances. You cannot perform any meaningful calculations or actions without creating an instance of a class first.
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
A Proxy object is a means for modifying the basic operations on an object. For example, the 'get' and 'set' operations can be altered.
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
The purpose of the 'MVC' design pattern is to give developers a predictable way to organize their code. It is especially important when many developers work on the same code base, as it gives them the ability to predict how the code used to accomplish a task was organized. For example, if a developer needs to make changes to the HTML that is printed to the page programattically, they know to look first in the relevant controller file. That file should either have the HTML directly in it, or be accessing a template held in a model file.
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
The controller's main job is to interact with the DOM directly through it's API, and it should be the *only* file type to do this. The DOM should only ever have function calls that route to a function within a controller file. The controller is then responsible for interacting with a service file appropiately. As part of it's responsiblity of interacting with the DOM, controller files should also draw all dynamic HTML elements to the page. This HTML data can be held directly within the controller files, or accessed via models.
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
The service's main job is to perform business logic. Business logic is defined as *creating, storing, or changing data*. An example of business logic would be taking in user input to create an instance of a model, and saving that model to Local Storage in the browser. An example of non-business logic would be taking a boolean value that was saved to memory, and evaluating the truthiness of that value to apply the attribute 'disabled' to a button on the page. That operation could take place in a controller file within the MVC template. the service files will need to interact with model files, the Appstate, or where ever data is being held, and the controller files. It is import that service files do *not* interact directly with the DOM.
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
The model's job is to hold classes that you will make instances of dynamically. These classes are how you will organize and store the bulk of your data. They can also store HTML templates and other display-related functions.
```

