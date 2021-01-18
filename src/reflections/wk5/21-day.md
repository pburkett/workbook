# Day 21
## __1/11/2021__

## what is the purpose of a query string?
The purpose of a query string is to further refine your HTTP request to a limited number of resources. A RESTful api should use queries to filter a resource down to items with properties that match your query.

## What is the format of a query parameter? How does it start? How do you distinguish between one parameter and the next?
A query parameter with 2 values might look like this: `?key=value&key1=value1`. The ampersand distinguishes the two key-value pairs.

## When do you think query parameters would be helpful when writing your server?
Query parameters can be built to handle many use cases on a server. For example, you can append other data, like ID's, to queries. You can also give a lot of options for how the client may requrest data via queries.