# Day 22
## __1/12/2021__

## What are the three types of relationships?
Data relationships take the form of one-to-one, one-to-many, and many-to-many.

## What are the benefits of the traditional linked relationships compared to embedded?
Embedded relationships do not scale as well as linked relationships. For example, a very long list of related and embedded items could exceed the memory alloted to an item in storage more easily than an unembedded item. Embedded relationships are also problematic when we have multiple relationships between sets of data. We could have a one-to-many relationship between posts and comments, and also have a one-to-many relationship between comments and user profiles ( for example, Reddit allows you to view any user's comment history).  If all comments were embedded within their respective post, it would be impractical to retrieve comments by one author, across many posts. Linked relationships can handle this situation better; we can store posts and comments separately, and give them foreign keys to represent their relationships.

## What are some of the challenges faced when deciding how to manage a many-to-many relationship that ultimately drive your decision on how to create it?
When deciding how to represent a many-to-many relationship in a databse, it's important to consider the ratios you expect in that relationship. For example, if you expect one side of your relationships to have relatively few relationships, it may make sense to store foreign keys within that document. For example, you may have a many-to-many relationship between contractors and houses. One house is likely to have a limited number of contractors associated with it, but a contractor may easily have hundreds of past jobs. This relationship is still many-to-many, but is severely lopsided. Listing foreign contractor keys on your house document may be an effective way to represent this relationship. The number of contractors per house may vary, but it's safe to say that the list should take up a managable amount of space. 
