# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
It's basically the big import and export of a file, you can put files in the same namespace and then they can use each other's stuff :)
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
Structs are value types while classes are reference types, structs can't ingerit from other classes or structs, they're immutable, they gotta be small and have single type values I thiiiink, so basically the difference is that structs are wack and super limited compared to classes. Yuck!
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
uhhhh... new ClassName(); ? 😬
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
public
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
What data type is expected to be returned.
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
That the code won't freak out about it not being a proper method, missing some stuff. It can only be instantiated by through something else referring to it or containing it that isn't abstracted.
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
Having virtual as a keyword in the declaration of a function or class makes it so it can be modified/overridden by any class that inherits it.
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public, private, internal, and protected.
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
Only the things within that same class.
```