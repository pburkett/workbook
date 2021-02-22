# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
Namespaces provide enforced encapsulation and organization for our program.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
In a struct, the default access modifier of all variables and methods is public.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
The constructor.
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
`Public` is the access modifier of the above method.
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
`string` is the expected return type of the method `Start()`
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
The flag `abstract` means the class cannot be instantiated.
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
The `virtual` flag marks a method as available for overriding.
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
The 4 main access modifiers are Public, Private, Internal, and Protected.
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
The private access modifier allows only sibling members to access a member. For example, a public method can be used to access a private property.
```