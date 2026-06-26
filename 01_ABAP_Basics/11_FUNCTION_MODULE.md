# Function Module in SAP ABAP

## Definition

A Function Module is a reusable block of code used to perform a specific task. It can be called from multiple ABAP programs.

---

## Why do we use Function Modules?

* Code Reusability
* Easy Maintenance
* Centralized Business Logic

---

## Components

* Import Parameters
* Export Parameters
* Changing Parameters
* Tables Parameters
* Exceptions

---

## Example

```abap
CALL FUNCTION 'Z_ADD_NUMBERS'
  EXPORTING
    iv_num1 = 10
    iv_num2 = 20
  IMPORTING
    ev_result = lv_result.
```

---

## Real-Time Example

* Calculate Tax
* Validate Vendor
* Create Purchase Order
* Send Email

---

## Interview Questions

### What is a Function Module?

A reusable program stored in SAP Function Builder.

### Difference between Function Module and Method?

Function Module is created in Function Builder.

Method belongs to an ABAP Class (OOP).

---

## Best Practice

Create reusable logic inside Function Modules instead of writing the same code repeatedly.

---

## Summary

Function Modules improve code reusability and maintainability.
