# Foreign Key in SAP ABAP

## Definition

A Foreign Key establishes a relationship between two database tables.

---

## Why do we use Foreign Keys?

* Maintain data consistency
* Prevent invalid data entry
* Create relationships between tables

---

## Real-Time Example

**EKKO**

| Purchase Order |
| -------------- |
| 4500000010     |

**EKPO**

| Purchase Order | Material |
| -------------- | -------- |
| 4500000010     | MAT001   |

Here, **EBELN** in EKPO is linked to **EBELN** in EKKO.

---

## Advantages

* Ensures referential integrity
* Improves data validation
* Prevents invalid references

---

## Interview Questions

### What is a Foreign Key?

A Foreign Key links one database table to another.

### Why is a Foreign Key used?

To maintain relationships and ensure data consistency.

---

## Common Mistakes

* Incorrect key mapping.
* Missing primary key relationship.

---

## Best Practice

Always link the Foreign Key to a valid Primary Key.

---

## Summary

Foreign Keys establish relationships between tables and maintain data integrity.
