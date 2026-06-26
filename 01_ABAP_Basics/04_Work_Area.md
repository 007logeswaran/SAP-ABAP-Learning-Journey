# Work Area in SAP ABAP

## Definition

A Work Area is a structure used to hold a single record temporarily.

---

## Syntax

```abap
DATA ls_mara TYPE mara.
```

---

## Example

```abap
LOOP AT lt_mara INTO ls_mara.
  WRITE ls_mara-matnr.
ENDLOOP.
```

---

## Difference

| Internal Table          | Work Area         |
| ----------------------- | ----------------- |
| Stores multiple records | Stores one record |
| Prefix: lt_             | Prefix: ls_       |

---

## Interview Questions

### What is a Work Area?

A Work Area stores a single row of data temporarily.

### Why do we use a Work Area?

To process one record at a time from an Internal Table.

---

## Summary

Work Areas are commonly used with LOOP, READ TABLE, and SELECT statements.
