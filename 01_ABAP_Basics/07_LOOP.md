# LOOP Statement in SAP ABAP

## Definition

LOOP is used to process each record of an Internal Table one by one.

---

## Syntax

```abap
LOOP AT lt_mara INTO ls_mara.
  WRITE: / ls_mara-matnr.
ENDLOOP.
```

---

## Real-Time Example

```abap
LOOP AT lt_ekko INTO ls_ekko.
  WRITE: / ls_ekko-ebeln.
ENDLOOP.
```

---

## Why do we use LOOP?

* Read every record
* Display data
* Update records
* Perform calculations

---

## Interview Questions

### Why is LOOP used?

To process records stored in an Internal Table.

### Can LOOP be used without an Internal Table?

No.

---

## Common Mistakes

* Forgetting ENDLOOP.
* Using LOOP on an empty Internal Table.

---

## Best Practice

Check if the Internal Table contains data before using LOOP.

---

## Summary

LOOP is one of the most frequently used statements in SAP ABAP.
