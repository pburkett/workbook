# Day 11
__12/14/2020__

## What problem does using exports solve?
Using exports in JavaScript allows us to organize our code into multiple files. JavaScript can theoretically handle a file size of any length, but for human software developers, keeping our files roughly under 200 lines helps us work efficiently. One file can have many classes, functions, and other kinds of data, but that file should have a limited number of tasks overall. This allows us to easily view and understand distinct portions of a code base.

## How does 'export' differ from 'export default'?
Both 'export' and 'export default' accomplish the same basic task. However, using 'export default' will stop anything else from being exported from that file. Exporting as default is a good practice if you want to export only one class or function, and you don't want to accidentally export anything else. Importing a default export has unique syntax, too. The standard import syntax is "import {importName} from 'file.js'". When importing a default export, the curly braces are not needed, and only one name can be given.

## What is a benefit of using the module system?
The module system allows us to use file exports and multiple files for our JavaScript code. The module system also provides us a basic level of encapsulation, because not all the data is available for manipulation at the level of our main JS file.