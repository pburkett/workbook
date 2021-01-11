# Day 13
__12/16/2020__

## What are the two common operations that we will set in the handler?
The two most common operations that we will set in a Proxy handler are the 'get' and 'set' operations. By setting these operations with a handler, we can set fail conditions for the operations, control what is returned, and run additional code. 

## What do you have to make sure that you are doing with every Get to ensure the value does not become 'undefined'?
When you set a get operation, you will override the default action of the get operation. The default action is simply to return the value stored under the key you provided. If you don't redefine the default get behavior and you try to access it, you will get the value of undefined. The default behavior of a get operation is as follows:
`get: function(obj, prop) {
    return obj[prop];
}`

## What are some of the benefits of the proxy objects that we are using in our structure for applications?
The main benefit of using the proxy objects in BCW's MVC code template is that we don't have to call a draw function everytime we make a change to our data. When we perform a set operation on our data that is drawn to the DOM, (There are a few ways to change a value without actually performing a set operation, most notably '+=' syntax, which has caused me some headache!) we will typically want the DOM to immediately update accordingly. A proxy object can automatically redraw to the DOM when a change is made to our data.