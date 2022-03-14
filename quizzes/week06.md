# Single Page Applications with Vue

**1.** What is the entrypoint of an application?
<!-- enter you answer in the space below -->
```
The entrypoint of an application can be most easily explained by the services. The service tells the server what data it wants and allows the data to talk to the server and enter into the application. 

```
**2.** What is the difference between a vue `component` and `page`?
<!-- enter you answer in the space below -->
```
A vue component is an "element"  in which can be found on a page. For example, forms, search bars, articles or posts, and so on. A page can be redirected to with vue, a component is loaded onto the page when the page is accessed.

```
**3.** What feature of Vue can be used to repeat an element using a collection of data?
<!-- enter you answer in the space below -->
```
V-for can be used to iterate the same data types in a collection to draw multiple things to a page. An example of this is a post say on facebook. A post has one blueprint or is consituent of one component but the component may hold different data from one object to the next. 

```
**4.** What are the three tags that make up a Vue component?
<!-- enter you answer in the space below -->
```
<template/> <script/> <style/>

```
**5.** What does the `L` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Liskov substitution principle. In a boiled down explaination, this principle states that the code we write, if new data or implementations are made such as a new version or replaced data, the code itself should be able to handle these changes and the functionality of it should not change. An example of this would be the change from windows xp to windows 7. The same windows OS exists with all of it's functionality but new data and features were added. Sidebar - anything made after windows 7 is garbage but I'll still use it.

```
**6.** Which component in Vue does the vue-router use to mount pages onto?
<!-- enter you answer in the space below -->
```
Vue uses the 'router' to route pages from one to the next. We can define our own paths in view and still maintain a single page application

```
**7.** What is the difference between the `AppState` and the state object within a component?
<!-- enter you answer in the space below -->
```
AppState can be accessed globally across the application but state object aka props are data utilized that has been passed from the parent likely accessing the Appstate.

```
**9.** What is the responsibility of `Services` in our Vue projects?
<!-- enter you answer in the space below -->
```
Services in vue prjects are responsible for acting as the hub for data transfer. They send data to our pages, our AppState, and access data from the server.

```
**10.** Which file contains the root element of your Vue project?
<!-- enter you answer in the space below -->
```
App.vue containes the root element. App.vue is the face of the DOM in vue.

```
**11.** The ______ tag is used to alter the styling of your entire Vue project.  Adding the ______ attribute to this tag will limit it to just the component it exists.  Fill in the blank.
<!-- enter you answer in the space below -->
```
:style, :scope

```
**12.** What is the Vue method used to create watchable objects such as `state` or `AppState`?
<!-- enter you answer in the space below -->
```
watchEffect and computed are two that work similar.

```