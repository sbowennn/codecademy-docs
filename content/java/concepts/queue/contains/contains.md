---
Title: '.contains()'
Description: 'Checks whether a string contains a specific sequence of characters - substring - exists within the given string.'
Subjects:
  - 'String Manipulation'
  - 'Object-Oriented Programming'
Tags:
  - 'String'
  - 'Collections'
  - 'Data Structures'
  - 'Methods'
---

# Description of .contains()

In Java, the **`.contains()`** method checks whether a string contains a specific sequence of charaters (substring) exists within a given string. This method is case-sensitive and the return is a boolean. If the string or substring is found (exists), it returns `true`. If it is not found (does not exist), it returns `false`. Finally, if the argument `null` is passed, the output will be `NullPointerException`.

## Syntax

```
public boolean contains()
```


## Example 1: Usage of `.contains()`

This example demonstrates how `.contains()` is used to inspect the next element without removing it from the queue:

```java
public class Main {
  public static void main(String[] args) {
    // Checks if a sequence of characters
    // is present the given string or not.
    String sentence = "Hello, Java!";

    // Checks if a sequence contains "Java"
    boolean present1 = text.contains("Java");
    System.out.println(present1);
    
    // Checks if a sequence contains "HTML"
    boolean present2 = text.contains("HTML");
    System.out.println(present2);
   
  }
}
```

The output for present1 and present2 is:

```shell
true
false
```


## Example 2

This example shows how case-sensitive the `.contains()` method is:

```java
public class Main {
  public static void main(String[] args) {
    // Checks if a sequence of characters
    // is present the given string or not.
    String sentence = "Hello, Java!";

    // Checks if a sequence contains "Java"
    boolean present1 = text.contains("Java");
    System.out.println(present1);
    
    // Checks if a sequence contains "HTML"
    boolean present2 = text.contains("java");
    System.out.println(present2);   

  }
}
```

The output for present1 and present2 is:

```shell
true
false
```

These examples demonstrate the function of the `.contains()` method. It is commonly used to search substrings, for validation, and filtering.