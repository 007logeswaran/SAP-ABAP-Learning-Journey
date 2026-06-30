# Structure in SAP ABAP

## Definition

A Structure is a collection of fields grouped together under a single name. Unlike a Database Table, a Structure does not store data permanently.

---

## Why do we use Structure?

Structures are used to hold related fields temporarily and transfer data between programs.

---

## Example

Employee Structure

| Employee ID | Employee Name | Department |
| ----------- | ------------- | ---------- |
| 1001        | Logeswaran    | IT         |

---

## Real-Time Example

A Purchase Order Structure may contain:

* Purchase Order Number
* Vendor Number
* Purchase Order Date

---

## Difference

| Database Table          | Structure           |
| ----------------------- | ------------------- |
| Stores data permanently | Does not store data |
| Database Object         | Memory Object       |

---

## Interview Questions

### What is a Structure?

A Structure is a group of related fields that does not store data permanently.

### Can we insert records into a Structure?

No. Structures are only used for temporary data storage.

---

## Common Mistakes

* Confusing Structure with Database Table.
* Expecting Structures to store data permanently.

---

## Best Practice

Use Structures for temporary processing and data transfer.

---

## Summary

A Structure groups related fields but does not store data permanently.
