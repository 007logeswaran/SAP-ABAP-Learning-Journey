# Object-Oriented Programming (OOP) Basics in SAP ABAP

## Definition

Object-Oriented Programming (OOP) is a programming approach where code is organized into Classes and Objects.

---

## Main Concepts

* Class
* Object
* Method
* Attribute
* Inheritance
* Polymorphism
* Encapsulation

---

## Example

```abap
CLASS lcl_employee DEFINITION.
  PUBLIC SECTION.
    METHODS display.
ENDCLASS.

CLASS lcl_employee IMPLEMENTATION.
  METHOD display.
    WRITE 'Hello ABAP'.
  ENDMETHOD.
ENDCLASS.
```

---

## Advantages

* Reusable Code
* Easy Maintenance
* Better Organization
* Scalable Applications

---

## Interview Questions

### What is a Class?

A Class is a blueprint used to create Objects.

### What is an Object?

An Object is an instance of a Class.

### What is a Method?

A Method is a function inside a Class.

---

## Best Practice

Use OOP for developing modern SAP applications.

---

## Summary

OOP improves code quality, readability, and reusability in SAP ABAP.
