# Variables in Java

## What is a variable?

A variable is a named container used to store data.

Think of it like a labeled box that holds a value.

---

## Why do we use variables?

We use variables to:
- store data
- reuse values
- make programs dynamic instead of fixed

---

## Syntax

```java
int age = 24;
String name = "John Doe";
```
---
## Types of variables
---

## 1. Primitive types

Store simple values.

Examples:

int → whole numbers
double → decimal numbers
boolean → true/false
char → single character

Example:
```java
int speed = 100;
boolean isActive = true;
```

---

## 2. Reference types

Store objects.

Example:

String name = "Java";

Here, String is an object type.

Key idea

A variable has:

- type
- name
- value

Example:
```java
int speed = 100;
```

int → type
speed → name
100 → value
Important rules
Java is strongly typed (type matters)
variable names are case-sensitive
cannot use reserved keywords as names
Common mistake

Thinking variables store the object itself.

They actually store:

primitive value OR
reference to an object