# C# Fundamentals

**1.** What is the purpose of a `namespace`?

<!-- enter you answer in the space below -->

```
A namespace establishes a relationsip and allows the use of the "using" key word.
```

**2.** What is the difference between a `class` and a `struct`?

<!-- enter you answer in the space below -->

```
A struct is a value type and class is a reference type.
```

**3.** What is the method that returns an instance of a class, yet it has no return type?

<!-- enter you answer in the space below -->

```
A constructor.
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
The data type.
```

**7.** In the example what is `abstract` preventing?

<!-- enter you answer in the space below -->

```
It is preventing inheritance.
```

**8.** In the example what is the purpose of `virtual`?

<!-- enter you answer in the space below -->

```
Virtual allows the method to be overridden in a derived class.
```

**9.** Name four access modifiers:

<!-- enter you answer in the space below -->

```
Public, private, protected, and internal.
```

**10.** If you set a class or method to private, what can access it?

<!-- enter you answer in the space below -->

```
Only code in the same class.
```
