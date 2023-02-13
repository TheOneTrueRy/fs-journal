# UnderStanding Asynchronous Code, and API's

**1.** What is the difference between `asynchronous` code and `synchronous` code?
<!-- enter you answer in the space below -->
```
Synchronous code is just normal code that runs in sequence, while asynchronous code involves at least some code that will run later or "in the future" to some degree (what asynchronous means) and therefore other code can run while that async code is still being processed. Ya dig?
```
**2.** What is an event listener?
<!-- enter you answer in the space below -->
```
A guy you hire that does a function anytime a piece of appState data is fucked with. :)
```
**3.** What does the `O` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
"Open-Closed Principle"
```
**4.** What is a callback / higher order function?
<!-- enter you answer in the space below -->
```
A callback is a function that can be defined by two characteristics: It is accessible by another function and it is invoked after the first function IF that first function completes.
```
**5.** What is a `promise`? How do you capture an error from a `promise`?
<!-- enter you answer in the space below -->
```
A promise is an object or representation of the eventual completion or failure of any async operation. You have to CATCH an error from a promise with something like a .catch or a trycatch.
```
**6.** Name three processes used to make requests over `HTTP`?
<!-- enter you answer in the space below -->
```
get, put, post, delete. Technically slap some .'s on the front of em and ()'s on the end.
```
**7.** What does the `API` acronym stand for?
<!-- enter you answer in the space below -->
```
Application Programming Interface
```
**8.** In the `MVC` design pattern, who is responsible for making calls to `APIs`?
<!-- enter you answer in the space below -->
```
The SERVICE. Which is... the S. In MVC. That doesn't make much sense... or maybe cense...
```
**9.** What is the purpose of encapsulation in programming?
<!-- enter you answer in the space below -->
```
STOP those pesky users from getting at info THEY SHOULDN'T HAVE!
```
**10.** What is `HTTP` response code for a successful request?
<!-- enter you answer in the space below -->
```
200. OK.
```
**11.** What is a 500 error?
<!-- enter you answer in the space below -->
```
Internal Server Error (insert cat meme here)
```