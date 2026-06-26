# SELECT Statement in SAP ABAP

## Definition

The SELECT statement is used to retrieve one or more records from a database table.

---

## Syntax

```abap
SELECT *
  FROM mara
  INTO TABLE lt_mara.
```

---

## Real-Time Example

```abap
DATA: lt_ekko TYPE TABLE OF ekko.

SELECT *
  FROM ekko
  INTO TABLE lt_ekko.
```

This program retrieves all Purchase Order Header records from the EKKO table.

---

## Why do we use SELECT?

* Read data from SAP database
* Store records in an Internal Table
* Process data using LOOP
* Display reports using ALV

---

## Interview Questions

### What is SELECT?

SELECT is an Open SQL statement used to retrieve data from SAP database tables.

### Where is SELECT commonly used?

Reports, ALV Reports, Smartforms, BDC, and BAPI programs.

---

## Common Mistakes

* Using `SELECT *` when only a few fields are required.
* Forgetting the WHERE condition.

---

## Best Practice

Select only the required fields to improve performance.

---

## Summary

The SELECT statement is the most commonly used statement for reading data from SAP database tables.
