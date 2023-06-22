
# Day 4 - 21st June 2023 

## Q1. What are function constructors?
    - A function constructor is a way to create a object using a function as a blue print or template.
    - it allow you to define a reusable structure for creating multiple object with similar properties and method.

## Q2. Explain call(), apply() and, bind() methods. Give an example of call(), apply(), bind()

    - These all three methods are used to invoke a function where we are supposed to pass an object as first argument and at the time of definition we don't have mention this object as a parameter and we can access the values of object by using this keyword in function definition.
    - Call : The call method is used to invoked a function with a specific 'this' value, and arguments provide individuly.
    - The call() method invokes a function in which first argument will be the object and rest of the arguments required by function will be provided as an individual arguments.
    - Apply : Apply is similar with call, but take argument as an array.
    -  The apply() method invokes a function in which first argument will be the object and rest of the arguments will be passed as an array of elements.
    - Bind - Bind is a function that helps you create another function that you can execute later with the new context of this that is provided.
    - The bind() method returns a new function and this function will be having the reference of the object passed, now whenever you want to use this returned function in the code you can use it by passing rest of the arguments.

## Async/Await - 
    - An async function is a function declared with the async keyword, and the await keyword is permitted within it. The async and await keywords enable asynchronous, promise-based behavior to be written in a cleaner style, avoiding the need promise chains.


## Inheritance:
    - Inheritance is a fundamental concept in object-oriented programming that allows objects to inherit properties and methods from other objects. It enables code reuse, promotes modularity, and facilitates the creation of hierarchical relationships between objects.
    - In JavaScript, inheritance is typically achieved through prototype-based inheritance. Objects in JavaScript can have a prototype, which is another object from which they inherit properties and methods.

## Prototype:
    - The prototype is an object that is associated with every JavaScript object. It serves as a blueprint or template for creating new objects through inheritance. The prototype object contains properties and methods that are shared among all instances created from it.
    - 