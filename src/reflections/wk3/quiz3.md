# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
Encapsulation, Abstraction, Inheritance, and Polymorphism.
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
staff['property']
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
Encapsulation is the idea of public and private functions used to interact with a class.  Methods are provided to control what types of interactions are allowed between objects instead of using direct access.
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single Responsibility
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
A class is the pattern or blueprint.  An instance of a class is an actual object created using that pattern or blueprint.
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
A proxy object is like a copy of an object. Proxies allow for customization of how objects interact with eachother. Getters and Setters are examples of how proxy objects can be used to provide more useful information or filter interactions with objects.
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
MVC helps with creating Single Responsiblitiy withing programs.
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
The controller accepts inputs and sends commands to the model or view.
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
The service contains the business logic.  It is an extra layer between the controller and the state or store.
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
The model(s) provide the model for the objects used within the program.
```

