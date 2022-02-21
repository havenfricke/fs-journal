# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
Abstraction - Limiting what parts of your code can be accessed either through functions or Prototype chains.

Encapsulation - Each object in your code should control it's own state. Properties of that object that are changed alter the state of your object. Using closures is how we create private property. A closure is function inception - you gain access to an outlying function's scope by using a function inside of itself.

Inheritance - Allows one object to access the properties and methods of another object. There is a technique called prototypal inheritance that allows us to accomplish this. 
  const F = function () {
    this.a = 1;
    this.b = 2;
  }
  const o = new F(); // const o's properties are now {a : 1, b: 2}

Polymorphism - "The condition of occurring in several different forms" - The core concept is to take HTML forms and perform a single action with those multiple forms.

```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->
```
let hisName = "Tim";
let tim = staff[hisName];

```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
A process that binds data with functions that work to access that data.

```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single responsibility principle. A class should have one and only one reason to change. Each class solves one problem.  

```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->

```
Classes are blueprints to the data which are used to create objects. An object that carries information of the class blueprint is an instance of the class.

```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
Enables you to create an object that takes the place of an original object with a target and handler.

let proxy = new Proxy(target, handler)

target - and object to wrap

handler - object containing methods to control the behavior of the target. Methods inside of the handler are referred to as traps.

Define object:
const user = {
    firstName: 'John',
    lastName: 'Doe',
    email: 'john.doe@example.com',
}

Defining a handler object:
const handler = {
    get(target, property) {
        console.log(`Property ${property} has been read.`);
        return target[property];
    }
}

create a proxy object:
const proxyUser = new Proxy(user, handler);

console.log(proxyUser.firstName);
console.log(proxyUser.lastName);

```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
To divide related logic into three elements that are interconnected. The overarching purpose of that is to separate concerns. Software components should do one thing under the single responsibility principle in solid. Model = business logic. Business logic goes in the models - business logic is what it sounds like. What the business the site is being created for is logically trying to present.
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
The job of the controller in the mvc patter is to take information from the HTEML portion and via listener, send to the service.
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
The job of Service in the MVC model is to take in the data from the controller and use the model to structure this data view object properties and functions that may inclue string interpolation with said data from the model.
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
The job of the model is to hold functions with enclosed objects called classes to hold a blueprint for the data and contain the business logic of the software functionality. 

```
