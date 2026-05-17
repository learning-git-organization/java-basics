
# Methods in Java

---
## What is a Method?

A method is a block of code that performs a specific task.

Think of it as a reusable action.

---

## Why do we use methods?

- avoid repeating code
- organize logic
- make programs readable
- break problems into smaller parts

---

## Basic Syntax

```java id="m2"
returnType methodName(parameters) {
    // code
}
````

---

## Example Method

```java id="m3"
class Car {

    void drive() {
        System.out.println("Car is driving");
    }
}
```

---

## Calling a Method

```java id="m4"
Car myCar = new Car();
myCar.drive();
```

---

## Types of Methods

### 1. Void Methods (no return value)

These methods perform an action but return nothing.

```java id="m5"
void printMessage() {
    System.out.println("Hello");
}
```

---

### 2. Return Methods

These methods return a value.

```java id="m6"
int add(int a, int b) {
    return a + b;
}
```

Usage:

```java id="m7"
int result = add(2, 3);
```

---

## Parameters vs Arguments

### Parameters

Variables defined in method declaration

```java id="m8"
int add(int a, int b)
```

### Arguments

Actual values passed when calling method

```java id="m9"
add(2, 3);
```

---

## Key Idea

Methods are used to:

* take input
* process logic
* optionally return output

---

## Simple Mental Model

Method = Input → Process → Output (optional)

---

## Important Rule

A method should ideally do ONE job only.

---