# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
The file 'package.json' tracks dependencies for a project. NPM will use package.json to install these dependencies.
``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
Your two dependencies files need to be at the top level of your server and client folders respectively, so Heroku can load these dependencies for you.
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
In order to create a Vue deployment, we can use `vue build` to 'build' a compilation that is ready for deployment.
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
`Environment variables`
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```

```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
Pushing code to the main branch on GitHub (or whatever branch heroku has been instructed to deploy from) will automatically update a Heroku app.
```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
Branching is most important when we complicate the development process: by bringing in multiple developers or with active deployment alongisde development. These complications mean that we want more space to stage our code before it runs in deployment.
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
Code review should happen, at a minimum, at the end of every sprint when developing with Agile methods. Code review can also be done whenever major portions of the application become completed.
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
When two branches join, its called a `merge`.
```
