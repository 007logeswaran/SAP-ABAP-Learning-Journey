# Variables in SAP ABAP

## Definition

A variable is a named memory location used to store data temporarily during program execution.

---

## Syntax

```abap
DATA lv_num TYPE i.
DATA lv_name TYPE string.
```

---

## Naming Convention

| Prefix | Meaning         | Example  |
| ------ | --------------- | -------- |
| lv_    | Local Variable  | lv_num   |
| gv_    | Global Variable | gv_count |

---

## Example

```abap
DATA lv_age TYPE i.

lv_age = 25.

WRITE lv_age.
```

Output:

```
25
```

---

## Real-Time Example

```abap
DATA lv_vendor TYPE ekko-lifnr.
```
This variable stores the Vendor Number from the Purchase Order Header table.

## Interview Questions

### What is a variable?

A variable is a temporary memory location used to store data during program execution.

### What is the difference between lv_ and gv_?

lv_ → Local Variable
gv_ → Global Variable

---

## Summary

Variables are used to store temporary data while the ABAP program is executing.
