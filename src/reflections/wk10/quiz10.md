# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
namespace's are used to to provide the compiler a context for all the named information in your program.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
classes are reference types, structs are value types.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
void
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
type of return
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
Abstract is preventing the class from being instantiated.
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
virtual is overriding the abstract class and allowing the class to be implemented. 
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public, private, internal, protected
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
If the access modifier is set to private only classes and methods can only be accessed by code in that same class. 
```