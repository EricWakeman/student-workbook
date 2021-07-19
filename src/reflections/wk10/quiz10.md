# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
it assings a directory to access the classes via the 'using' method.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
struct has non nullable parameters while class params can be nullable
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
static void
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
: Car {Start()}
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
the return data type in the method.
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
abstact prevents the class from being obstantiated on its own
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
virtual can be inherited by other classes
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public private protected internal
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
only by code that shares the class or struct
```