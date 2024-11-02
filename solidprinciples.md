# What are S.O.L.I.D principles?
These are the principles that are used to build softwares by ensuring the scalability, integrity of the software. These principles were introduced by the famous software Engineer [Robert C martin](https://en.wikipedia.org/wiki/Robert_C._Martin).

Let's go through every principle.

## 1. Single Responsibility

 ### A class should have only one single responsibilty
 
 This principle states that the class should have only one single responsibility , if there are more than one responsibility it might lead to unexpected behaviour of the class so it is best practice to give single responsibility to a class.
 
 ## 2. Open and Closed 
 
 ### The class should be closed for modification, Open for extension 
 
 This principle states that a class should be closed for modification that means the main functionality of a class should not be modified, rather it should be open for extension the new functionality should be added without affecting the primary functionality of the class.
 
 ## 3. Liskov Substitution

### The child class should be able to replace the parent class

Let's say there is a class B subtype of class A which means the class B extends class A.
Then in some scenario's the object of the class B should replace the class A object since the child classes have the properties and behaviour of the parent class.

## 4. Interface segregation

### Clients should not be forced to depend on methods that they do not use.

This principle states that the set of actions should be split into smaller parts so that it can maintain consistency. The class should only perform the methods that it can perform , if it tries to perform the actions it was not desgined to it, it will produce many bugs so it is best practice to segregate the interfaces.

## 5. Dependency Inversion
- **High-level modules should not depend on low-level modules. Both should depend on the abstraction.**
- **Abstractions should not depend on details. Details should depend on abstractions.**

  To understand this you need to understand the concepts of low level and high level modules.

* High level modules
  Class that executes an action with a tool.  
*Low level modules
The tool that is needed to execute the action

This principle says a Class should not be fused with the tool it uses to execute an action. Rather, it should be fused to the interface that will allow the tool to connect to the Class. It also says that both the Class and the interface should not know how the tool works. However, the tool needs to meet the specification of the interface.

References :

[Medium](https://medium.com/backticks-tildes/the-s-o-l-i-d-principles-in-pictures-b34ce2f1e898)
[GFG](https://www.geeksforgeeks.org/solid-principle-in-programming-understand-with-real-life-examples/)










