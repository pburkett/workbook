 # Day 2
 __12/01/2020__
 
 ## What is a Pseudo-Class and what are some of the most common ones you think you will use?
    A pseudo-class is a CSS class that applies it's attributes when certain parameters are met. For example, the ':hover' pseudo class is applied when the element has the mouse hovered over it. I think the hover pseudo class is the most useful for simple aesthetic purposes for the user.

 ## What is Specificity and how might you use it to your benefit? 
    Specificity is the priority with which a CSS selectors attributes are applied. Selecting by different means will produce different specifities; for example, selecting by id will give a higher specifitity than selecting by class. Specificity can be used to override attributes that have been applied by other means. For example, it's common to override attributes that have been applied by a class provided by a framework like Bootstrap.

## What problems do you think you could run into if you over-utilized the !important feature?
    The !important feature immediately raises the priority of an attribute by 1000, which is a lot. Using this without care can lead to messy code down the road. For example, if you wish to override an attribute that comes from a class with the !important tag, you will need two !important tags. To avoid this, it is wise to use only the specificity you really need to override another attribute. For example, selecting by id can often give you the specificity needed.
