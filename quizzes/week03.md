# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
Abstraction, Encapsulation, Inheritance, Polymorphism.
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
let property = staff.name
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
Containing information inside an object so you're only exposing select information to the outside and probably stupid or malicious world.
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single Responsibility
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
A class is the blueprint you use to create objects, and those objects are *instances* of that class.
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
A 'Proxy' object is what you create to be used in place of an original object, but can redefine fundamental object operations.
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
Organization, easier use of tons of files, it's pretty nice.
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
Place where functions that players or users can actually access go. Sends stuff to Service for when data manipulation comes into play. Press a on controller, that gets taken in here.
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
Controller directs here, actually manipulates data and reaches into the AppState and does all kinds of stuff. Press a on controller, and THIS is where it actually makes your guy jump.
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
Be the model class (blueprint) of an object that you will use in other things.
```
