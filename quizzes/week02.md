# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
let, var, and const

```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
An activity carried out by mathematics with an intended purpose and uses at least one variable to dtermine what the function will do.

```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Solid principles are guidlines when using JavaScript that keep code clean and functional.

S - single responsibility: code written in terms of functionality have a single responsibility.

O - Open-closed principle: Objects are extendable but closed for modification.

L - Liskov substitution: Any superclass object can be substituted with a subclass.

I - Interface Segregation Principle: clients should not implement an interface it will not use.

D - Dependancy Inversion Principle: High level modules cannot depend on lower level modules. Both must depend on an abstraction.

```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
The current index position of the 'pineapple' is i = 2. An array by default starts at poistion 0 and goes up from there.

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

console.log(you)

```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
if, else, else if, do while are conditionals.
and example of such is:

function isTrue(){
if (pineapple == pineapple) { return }
console.log('true') 
if (pineapple == apple)
console.log('false')
}

**This is techically two conditional statements in one function

```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
That is the third statement in a for loop. We would indicate how we move through our index with this statement. If we wanted to move up in position when accessing info from the array, we would say i++.
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
Document object model - The first file access and rendered by the DOM is our index.HTML.

```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
Our 9 data types include strings, numbers, boolean, null, undefined, symbols, bigint, objects, and array.

```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
An argument sits outside of a function typically as a variable. A parameter is a reference to a variable inside of our functions. The main difference is the location in which they are used and their primary function. When a function calls, the values passed are arguments. Parameters are the variables we define in the function declaration.

```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
Primitives are essentially data types. references arepointers in which do not hold values but instead point to their values. Variables are subdivided into primitive and reference. Primitive is a value stored as a variable, a reference is a variable that references information related to the variable.

```