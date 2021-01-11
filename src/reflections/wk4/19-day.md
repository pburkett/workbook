# Day 19
## __1/7/2021__

## What does REST stand for, and in simple terms, what does it mean?
REST stands for representational state transfer. REST is a set of standards for creating API's. It means that an API should return the full state of any requested resource. For example, when I (or my browser) make a request for a resource, I should be given all the information stored under that resource, or the "state" of it.

## What does stateless mean?
In the context of RESTful API's, stateless means that the API does not remember information about the client. For example, the server should **not** save information about the client's last request, and use it to send less data about the state of a resource upon the next request.

## What URL pattern is used when writing a RESTful API?
URLs in RESTful APIs should look like: `resource/identifier/resource`, or shallower. For example, I'll look at the URLs of the Poke API. The URL for the resource "tepig" looks like this: `https://pokeapi.co/api/v2/pokemon/tepig`

`https://pokeapi.co/api/v2/` directs to a resource, which holds URLs that direct to other resources. One such resource is `pokemon`.

`https://pokeapi.co/api/v2/pokemon` directs to a resource, which holds URLs that direct to all 1118 Pokemon resources.

`https://pokeapi.co/api/v2/pokemon/tepig` directs to a resource which holds the full state of Tepig, one of many Pokemon. Individual pokemon can also be located by ID. For example, `https://pokeapi.co/api/v2/pokemon/498` also directs to the Tepig resource.

# Daily Project:
https://github.com/pburkett/itunes-wep-app

