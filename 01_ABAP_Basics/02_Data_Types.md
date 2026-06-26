# Data Types in SAP ABAP

## Definition

A data type defines what kind of data a variable can store, such as numbers, characters, dates, or time.

---

## Common Data Types

| Data Type | Description             | Example      |
| --------- | ----------------------- | ------------ |
| i         | Integer                 | 100          |
| c         | Character               | 'ABC'        |
| n         | Numeric Character       | '12345'      |
| string    | Variable length text    | 'Logeswaran' |
| d         | Date                    | 20260626     |
| t         | Time                    | 143500       |
| p         | Packed Number (Decimal) | 1250.75      |

---

## Example

```abap
DATA lv_age TYPE i.
DATA lv_name TYPE string.
DATA lv_date TYPE d.
```

---

## Interview Questions

### What is a data type?

A data type defines the type of value that can be stored in a variable.

### What is the difference between TYPE i and TYPE string?

* TYPE i stores integers.
* TYPE string stores text of variable length.

---

## Summary

Choosing the correct data type helps store data efficiently and prevents errors.
