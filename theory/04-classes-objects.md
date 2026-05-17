# Classes and Objects

---

## What is a Class?

A class is a blueprint used to create objects.

It defines:
- properties (variables)
- behavior (methods)

---

## Example

```java
class Car {
    int speed;

    void drive() {
        System.out.println("Car is driving");
    }
}
```
---
## What is an Object?

An object is a real instance of a class.

When a class is used in memory, an object is created.

Example:
```java
Car myCar = new Car();
```

### Key Idea
- Class = design
- Object = real thing created from design
- Memory Model (simple version)
- myCar → refers to Car object in memory

### Object lives in heap memory, variable holds reference.

## Why objects are used

### Because real systems are modeled as:

- users
- cars
- orders
- payments

### Each becomes an object.

### Important Rule

### One class can create many objects.

```java
Car c1 = new Car();
Car c2 = new Car();
```

### Each object is independent.

---