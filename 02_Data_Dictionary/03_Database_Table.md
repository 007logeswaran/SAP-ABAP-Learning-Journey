# Database Table in SAP ABAP

## Definition

A Database Table stores business data permanently in the SAP database.

---

## Why do we use Database Tables?

To store and retrieve application data such as Purchase Orders, Materials, Vendors, and Customers.

---

## Components

* Fields
* Data Elements
* Domains
* Primary Key

---

## Real-Time Examples

| Table | Purpose               |
| ----- | --------------------- |
| EKKO  | Purchase Order Header |
| EKPO  | Purchase Order Item   |
| MARA  | Material Master       |
| KNA1  | Customer Master       |
| LFA1  | Vendor Master         |

---

## Example

EKKO

| EBELN      | LIFNR  | AEDAT      |
| ---------- | ------ | ---------- |
| 4500000010 | 100001 | 26.06.2026 |

---

## Interview Questions

### What is a Database Table?

A Database Table stores application data permanently.

### Difference between Structure and Database Table?

Database Table stores data permanently.

Structure does not store data.

---

## Common Mistakes

* Confusing Structure with Database Table.
* Using unnecessary fields.

---

## Best Practice

Define proper Primary Keys and meaningful field names.

---

## Summary

Database Tables are used to permanently store business data in SAP.
