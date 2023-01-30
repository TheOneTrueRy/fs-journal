# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
let, var, and const
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
Well if you mean the definition of it like what is it, then a function is an object with properties, methods, and can be executed/invoked as many times as you want.

What is the definition of a function as in what is defining a function then:
"function functionName(parameters){code}"
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
The Single Responsibility Principle
The Open-Closed Principle
The Liskov Substitution Principle
The Interface Segregation Principle
The Dependency Inversion Principle
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
Index 2, because it is the third object/string in the array. Array's start at index 0 for the first item.
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
you.friends.push(them)
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
if(*conditional*){}
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
The iteration statement. i++ would increase i by one on every iteration.
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
The DOM is the document, the first file accessed in rendering the DOM is the index.html
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
Boolean, Number, Int, Null, String, Void, Symbol, Object
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
Parameters are what is put into the parenthesis of a function when you write and define the function, arguments are what you put into those parenthesis when calling/invoking that function.
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
Primitive values are a data type that is more static and independent like a defined number, string, boolean, etc. Reference values refer to objects. Primitive values can not have properties, while Reference values can.
```