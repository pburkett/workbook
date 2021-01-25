# Day 29
## __1/24/2012__

## What is a nested route?
A nested route is a route that paths through another route, and essentially follows a parent-child, typically one-to-many relationship.

## When might you use a nested route? (other than the provided example)
Route nesting could be useful when building a social media site that provides many small communities, such as sub-Reddits or Facebook groups. You might route your site through dynamically nested routes to organize many small sub-communities.

## Can you pass parameters through nested routes? When might you use them?
You can pass parameters through routes, following the familiar use of `:` withing the router. This would be useful anytime your routing is dynamic, and/or follows a `collection/ID` format in which you need access to that ID. This is probably pretty common in nested routes, considering that increased abstraction when representing one-to-many relationships is one of the main reasons to use a nested route.