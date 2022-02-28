# UnderStanding Asynchronous Code, and API's

**1.** What is the difference between `asynchronous` code and `synchronous` code?
<!-- enter you answer in the space below -->
```
Synchronus code works in a fashion that goes from one function to the nexxt and only when one function is completed, it then goes to the next. Asynchronus works in such a way that allows the function run based on the the server response.

```
**2.** What is an event listener?
<!-- enter you answer in the space below -->
```
An event listener is a device in which listens for changes in the data and also referes to specific functions that may be responsible for moving that data the is being listened to. If new data moves into an object or array and a listener is listening to it then a function can be invoked such as a draw function

```
**3.** What does the `O` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Open-Closed principle. Objects should be open for extension but closed for modification. Open in terms of extension meaning the object can be added to without harmign the current data constituent of that object. Closed meaning we should not introduce new things to the object that may break our code.

```
**4.** What is a callback / higher order function?
<!-- enter you answer in the space below -->
```
A call back is instructions to perform executable code when an event happens. Essentially a fuction that tells another function to do something when a specific event happens.

```
**5.** What is a `promise`? How do you capture an error from a `promise`?
<!-- enter you answer in the space below -->
```
A promise is either a try-catch or .then. Capturing an error with promises can be done by logging the error and reading whether or not the promise what kept in terms of what was fetched from the executed code.

```
**6.** Name three processes used to make requests over `HTTP`?
<!-- enter you answer in the space below -->
```
GET, POST, DELETE, PUT. The list goes on.

```
**7.** What does the `API` acronym stand for?
<!-- enter you answer in the space below -->
```
API stands for application programming interface.

```
**8.** In the `MVC` design pattern, who is responsible for making calls to `APIs`?
<!-- enter you answer in the space below -->
```
The service is responsible for making calls to the API but the service is lazy and usually needs some extra motivation from the controller.

```
**9.** What is the purpose of encapsulation in programming?
<!-- enter you answer in the space below -->
```
The purpose is to bundle code that performs similar tasks. A class is a good example of encapsulated code. Classes are packaged code functionality to perform a task related to the same data.

```
**10.** What is `HTTP` response code for a successful request?
<!-- enter you answer in the space below -->
```
Successful code response for HTTP are messages numbered 200-299.

```
**11.** What is a 500 error?
<!-- enter you answer in the space below -->
```
A 500 error is an internal server error. The server encounters a situation in which it does not know how to handle.

```