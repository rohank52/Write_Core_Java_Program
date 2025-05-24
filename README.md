# Core_java
Here's a concise **Core Java Concepts** summary formatted like a GitHub `README.md` file, ideal for quick reference or documentation.

---

# Core Java Concepts – Quick Guide

This document provides a short and clear overview of all key **Core Java** concepts. Suitable for interviews, revision, and documentation.

---

## 📌 Table of Contents

1. [Java Basics](#java-basics)
2. [OOP Principles](#oop-principles)
3. [Data Types & Variables](#data-types--variables)
4. [Control Statements](#control-statements)
5. [Arrays & Strings](#arrays--strings)
6. [Methods](#methods)
7. [Classes & Objects](#classes--objects)
8. [Inheritance](#inheritance)
9. [Polymorphism](#polymorphism)
10. [Abstraction & Interfaces](#abstraction--interfaces)
11. [Encapsulation](#encapsulation)
12. [Exception Handling](#exception-handling)
13. [Collections Framework](#collections-framework)
14. [Multithreading](#multithreading)
15. [File I/O](#file-io)
16. [Java 8 Features](#java-8-features)
17. [Memory Management](#memory-management)
18. [Miscellaneous](#miscellaneous)

---

## ✅ Java Basics

* Java is an object-oriented, platform-independent, high-level programming language.
* `JDK`, `JRE`, `JVM`:

  * **JDK**: Java Development Kit (includes compiler + JRE)
  * **JRE**: Java Runtime Environment
  * **JVM**: Java Virtual Machine (executes bytecode)

## ✅ OOP Principles

1. **Encapsulation**
2. **Inheritance**
3. **Polymorphism**
4. **Abstraction**

## ✅ Data Types & Variables

* **Primitive**: `int`, `byte`, `short`, `long`, `float`, `double`, `char`, `boolean`
* **Non-Primitive**: `String`, `Arrays`, `Objects`
* Variables: local, instance, static

## ✅ Control Statements

* **Conditional**: `if`, `if-else`, `switch`
* **Loops**: `for`, `while`, `do-while`
* **Branching**: `break`, `continue`, `return`

## ✅ Arrays & Strings

* Arrays: `int[] arr = new int[5];`
* String: Immutable, stored in string pool.
* StringBuffer (mutable, thread-safe), StringBuilder (mutable, non-thread-safe)

## ✅ Methods

* Syntax: `returnType methodName(params)`
* Method Overloading: same name, different params
* Pass by value only in Java

## ✅ Classes & Objects

* Class: Blueprint for object
* Object: Instance of a class
* Constructor: special method to initialize object

## ✅ Inheritance

* Acquiring properties from a parent class
* Types: Single, Multilevel, Hierarchical (Java doesn’t support multiple inheritance using classes)

## ✅ Polymorphism

* Compile-Time (Method Overloading)
* Run-Time (Method Overriding)

## ✅ Abstraction & Interfaces

* Hiding implementation, showing only functionality
* **Abstract class**: can have abstract + concrete methods
* **Interface**: 100% abstraction (Java 8 allows default & static methods)

## ✅ Encapsulation

* Wrapping data using classes and providing access via getters/setters
* Promotes data hiding

## ✅ Exception Handling

* Try-catch-finally
* `throws`, `throw`
* Checked vs Unchecked Exceptions
* Custom Exceptions

## ✅ Collections Framework

* Interfaces: `List`, `Set`, `Map`, `Queue`
* Implementations: `ArrayList`, `LinkedList`, `HashSet`, `HashMap`, `TreeMap`, `PriorityQueue`
* Utility class: `Collections`

## ✅ Multithreading

* Thread creation via `Thread` class or `Runnable` interface
* Thread lifecycle: New → Runnable → Running → Blocked → Dead
* `synchronized`, `wait()`, `notify()`, `sleep()`

## ✅ File I/O

* Classes: `File`, `FileReader`, `FileWriter`, `BufferedReader`, `BufferedWriter`
* Streams: `InputStream`, `OutputStream`, `ObjectInputStream`

## ✅ Java 8 Features

* **Lambda Expressions**: `(a, b) -> a + b`
* **Streams API**
* **Functional Interfaces**: `Runnable`, `Callable`, `Predicate`
* **Default & Static methods in Interfaces**

## ✅ Memory Management

* Stack (method call), Heap (objects)
* Garbage Collection: `System.gc()`, `finalize()`
* Reference types: Strong, Weak, Soft, Phantom

## ✅ Miscellaneous

* `static`, `final`, `this`, `super`, `instanceof`
* Packages & Imports
* Access Modifiers: `public`, `protected`, `private`, default

---

### 🛠 Sample Structure

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, Java!");
    }
}
```

---

Let me know if you want this exported as a `.md` file or want any section expanded or visualized.
