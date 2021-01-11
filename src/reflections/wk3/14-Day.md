# Day 14
__12/17/2020__

## What problems does the Observer patterm seek to solve?
The observer pattern seeks to solve a very common problem in web development. Often we want to make a change to data, and see that change reflected on the page. An observer pattern solves this by allowing us to call functions when our data is changed.

## What are the three mechanisms of the observer pattern?
The three mechanisms an observer pattern uses are subscribe, unsubscribe, and broadcast. The subscribe mechanism is how we list what function calls to make when the observer is triggered. the unsubscribe mechanism is how we perform the opposite action; we remove function calls from that list. Broadcasting is when we work through that list of function calls, and call each one.

## Review the code generated from the bcw-template and reflect on the proxy objects from yesterday, and your understanding of the observer pattern today. With this knowledge, explain how the 'magic' of the bcw-template uses these two concepts to manage and update the DOM.
The BCW-template 'magic' is actually less complicated than it first appeared to me. The ProxyState object in AppState.js has a method called 'on' which you can use to set new observers. You can then provide it with an Appstate.js value to watch, and the name of a function to call. When a set operation is performed on the value your observer is watching, the function you provided will be called.
