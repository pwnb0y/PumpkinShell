# Java CheatSheet

# Introduction and Background

1. Java is a high-level, class-based, object-oriented programming language that is designed to have as few implementation dependencies as possible. It is a general-purpose programming language intended to let programmers write once, run anywhere.
2. The syntax of Java is similar to C and C++, but has fewer low-level facilities than either of them. The Java runtime provides dynamic capabilities (such as reflection and runtime code modification) that are typically not available in traditional compiled languages.
3. Java was originally developed by James Gosling at Sun Microsystems. It was released in May 1995 as a core component of Sun Microsystems' Java platform. The original and reference implementation Java compilers, virtual machines, and class libraries were originally released by Sun under proprietary licenses.

# A. Comment In Java

Comments can be used to explain Java code, and to make it more readable. It can also be used to prevent execution when testing alternative code.

In Java we have two type of comment

1. single line comment

```java
// this is single line comment
System.out.print("hello world!") // hello world!
```

2. multi line comment

```java
/*
for (let i = 0; i<10; i++){
    System.out.println("you are in a loop")
}
*/
```

# B. Java Syntax

To run Java or to create Java file we should create file with _.java_ extension,

In java everything run on **class**, under class we have a **main** method (function: function is who lived in outside any class, and method: a function that live in side a class), under main method we write our code

```java
public class Main {
  public static void main(String[] args) {
    System.out.println("Hello World");
  }
}
```

# C. Java Variable

Variable are noting just a container that store data value

## Creating a variable

To create a variable, you should specify the type and give the value

```java

// type variableName = data
String outputString = "Hello world"

```

# D. Java Data type

as we know we container data in variable but we need some data type to store a variable, there comes Data type

In java we have primitive Data type and Non-primitive data

### Primitive data types

byte, short, int, long, float, double, boolean and char

```java
int myNum = 5;               // Integer (whole number)
float myFloatNum = 5.99f;    // Floating point number
char myLetter = 'D';         // Character
boolean myBool = true;       // Boolean
String myText = "Hello";     // String
```

### Non-primitive data

such as String, Arrays and Classes
