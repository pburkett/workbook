# Understanding Persistent Relational Data

**1.** When using the Vue `cli` what is the command to initialize a project?
<!-- enter you answer in the space below -->
```
`vue create` will open an interactive menu to assist with starting a project.
```
**2.** Where can you find the scripts to startup you project on localhost?
<!-- enter you answer in the space below -->
```
The script used to startup a server on localhost with Vue is called 'serve'.
```
**3.** What feature of Vue can be used to repeat an element using a collection of data?
<!-- enter you answer in the space below -->
```
`v-for` can be used to create multiple instances of a single component, using an array.
```
**4.** What are the three tags that make up a Vue component?
<!-- enter you answer in the space below -->
```
Vue components are composed of <template>, <script>, and <style>. These correspond to HTML, JS, and CSS respectively.
```
**5.** What does the `L` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
The 'L' in SOLID represents the Liskov Substitution principle. This states that types should be replacable with their subtypes without altering the 'correctness' of a program. Subtypes should still be able to perform the tasks their parent types can perform; when creating subtypes of any kind, the base functionality should be left intact.
```
**6.** Which component in Vue does the vue-router use to mount pages onto?
<!-- enter you answer in the space below -->
```
The vue router mounts pages into the App component. Your App.vue file serves as the entry point for all of the Vue in your program.
```
**7.** What is the difference between the `AppState` and the state object within a component?
<!-- enter you answer in the space below -->
```
AppState holds data which is accessible from anywhere in your program, with an appropiate import. Your AppState will never import any of your services and components, which means you can safely import AppState anywhere in your program. The state object within a component is only accessible from within that component. The state object is often used for data that is local to that component, for example, data that contrls how that component renders. 
```
**9.** What is the responsibility of `Services` in our Vue projects?
<!-- enter you answer in the space below -->
```
In Vue projects, Service files serve essentially the same function they do when using MVC in vanilla JavaScript. Services are responsible for manipulating data, and retreiving it from external sources (usually API calls). 
```
**10.** Which file contains the root element of your Vue project?
<!-- enter you answer in the space below -->
```
The root of a Vue project is in main.js.
```
**11.** The ______ tag is used to alter the styling of your entire Vue project.  Adding the ______ attribute to this tag will limit it to just the component it exists.  Fill in the blank.
<!-- enter you answer in the space below -->
```
`style`
`scoped`
```
**12.** What is the Vue method used to create watchable objects such as `state` or `AppState`?
<!-- enter you answer in the space below -->
```
`reactive` will create a watchable object.
```