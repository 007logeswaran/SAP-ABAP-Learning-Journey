# Internal Tables in SAP ABAP

## Definition

An Internal Table is a temporary memory area used to store multiple records during program execution.

---

## Syntax

```abap
DATA lt_mara TYPE TABLE OF mara.
```

---

## Real-Time Example

```abap
SELECT *
  FROM mara
  INTO TABLE lt_mara.
```

---

## Why do we use Internal Tables?

* Store multiple records
* Process data using LOOP
* Display data in ALV

---

## Interview Questions

### What is an Internal Table?

It is a temporary table used to store multiple records in memory.

### Can an Internal Table store one record?

Yes, but it is mainly designed to store multiple records.

---

## Summary

Internal Tables are one of the most important concepts in SAP ABAP and are widely used in reports and data processing.
