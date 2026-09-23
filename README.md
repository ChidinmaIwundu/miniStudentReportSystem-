# Java OOP Basics: Student Class

A small Java project that demonstrates the core building blocks of **object-oriented programming (OOP)**: defining a class, creating objects with a constructor, and calling methods on them.

---

## Overview

The project has two files:

| File | Role |
|---|---|
| `Student.java` | Defines the `Student` class with two fields, a constructor, and a method |
| `Main.java` | Creates a `Student` object and uses it |

---

## ▶️ How to Run

Make sure the [JDK](https://www.oracle.com/java/technologies/downloads/) is installed, then from the project folder:

```bash
javac Student.java Main.java
java Main
```

**Expected output**

```
Amara
10
Amara is in grade 10.
```

---

## 💡 Concepts Demonstrated

| Concept | Where it appears |
|---|---|
| **Class** | `Student` is a blueprint for student objects |
| **Fields (instance variables)** | `name` and `grade` store each student's data |
| **Constructor** | `Student(String name, int grade)` sets up a new object |
| **`this` keyword** | `this.name = name;` separates the field from the parameter with the same name |
| **Object creation** | `new Student("Amara", 10)` builds an object from the class |
| **Instance method** | `displayInfo()` acts on the data of the object that calls it |
| **Field access** | `s1.name` and `s1.grade` read the object's fields directly |


