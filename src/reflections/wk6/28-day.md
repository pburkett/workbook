# Day 28
## __1/24/2012__

## What are lifecycle hooks?
Lifecycle hooks are a set of keywords Vue provides that allow us to 'hook' code into specific stages in the lifecycle of a component.

## What are lifecycle hooks used for?
Lifecycle hooks are used whenever we need to perform actions in relation to the lifecycle of a component. 

## What are mounting hooks? When might you use them?
The `onMounted` hook will execute it's given code when the component is mounted to the DOM. This means the component will be fully instantiated and all methods will be available, but the component won't be rendered yet. It's common to use this to fire API calls from your service files for some simplistic lazy-loading in your application.
