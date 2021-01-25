# Day 26
## __1/24/2012__

## What is component based architecture?
Component architecture breaks a program down into many different components. A component is a functional piece of software on it's own; it contains all code required to make a small part of a program operational. A component will typically have it's own controller (this is the actual .vue file in Vue), a service, it's own data to manipulate (typically held in a global AppState) and potentially it's own models to help represent that data.

## What are some benefits of component base architecture?
Building with components helps us organize our software into *functionality-based responsibilities*. When working with components, it's easy to break down a program into groups of files that serve a single function. MVC allows us to break our software into *types of responsibilities*. For example, it's very easy to break an MVC program down into groups of files that handle business logic and data manipulation.

## What are some drawbacks to component based architecture?
The main drawback to component architecture is that sometimes, building components for a program is overkill. Not all programs are equal in complexity. For more simple programs, building components may increase the number of files and imports needed without much benefit in organization. Components can degrade readability if not used with forethought; simple programs or elements may not require component-ization.