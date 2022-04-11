# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
Namespace is an encapsulated envioronment for classes, methods, and other c# syntax.

```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
Struct is value types and class is reference types.

```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
Void is used for this purpose.

```
## Example 1
```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```
**5.** In the example what is the access modifier of the `Start()` method?
<!-- enter you answer in the space below -->
```
Abstract class Car is the access modifier since it is defining the scope of Start().

```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
String is an indicator of the return type of the method. In the scope of Start() "Vroooom" is return which is a string data type.

```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
Abstract i preventing a pre-compiling error message and is indicating that the method is left incomplete or without parameters and arguments to complete the method. This I likely for callbacks of methods.

```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
Virtual allows for a method to be overridden in derived classes. In this example, it is not being overridden.

```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public, protected, internal, private.

```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
Private methods can only be accessed within it's respetive class.

```