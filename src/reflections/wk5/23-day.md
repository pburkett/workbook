# Day 23
## __1/13/2021__

## In simple terms, what is a sub-document?
A sub-document is a mongoose document that is stored within another mongoose document. Handling sub-documents is similar to handling nested POJOs in vanilla JavaScript.

## When might you use a sub-document?
When representing a relationship via embedding, a sub-document is a good way to store the related data. We can access our related data through it's key.

## How do you add to a collection of sub-documents? What about editing them?
Making changes to a collection of sub-documents is similar to making changes in our appstate when working in MVC on the client. First, we need to locate the document to target within its collection (or in the client, the object within the array to target). Then, we target the specific array we would like to append onto or update. The key under which the subdocument is stored must be used to access it. Then, we can make our change and use the `save` method on the mongoose document.
