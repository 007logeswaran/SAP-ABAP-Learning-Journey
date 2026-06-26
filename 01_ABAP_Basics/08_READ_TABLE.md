# READ TABLE in SAP ABAP

## Definition

READ TABLE is used to retrieve a specific record from an Internal Table.

---

## Syntax

```abap
READ TABLE lt_mara INTO ls_mara INDEX 1.
```

---

## Real-Time Example

```abap
READ TABLE lt_ekko INTO ls_ekko INDEX 1.

IF sy-subrc = 0.
  WRITE ls_ekko-ebeln.
ENDIF.
```

---

## Why do we use READ TABLE?

* Read a single record
* Search data in an Internal Table

---

## Interview Questions

### What does READ TABLE do?

It retrieves one record from an Internal Table.

### What does sy-subrc = 0 mean?

The record was found successfully.

---

## Common Mistakes

* Forgetting to check `sy-subrc`.
* Reading an invalid index.

---

## Best Practice

Always check `sy-subrc` after READ TABLE.

---

## Summary

READ TABLE is used to search and retrieve records from an Internal Table.
