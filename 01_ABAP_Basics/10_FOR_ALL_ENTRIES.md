# FOR ALL ENTRIES in SAP ABAP

## Definition

FOR ALL ENTRIES is used to retrieve related records from another database table based on the values available in an Internal Table.

---

## Why do we use FOR ALL ENTRIES?

Instead of executing multiple SELECT statements inside a LOOP, FOR ALL ENTRIES retrieves all required records in a single database call.

---

## Syntax

```abap
SELECT *
  FROM ekpo
  INTO TABLE lt_ekpo
  FOR ALL ENTRIES IN lt_ekko
  WHERE ebeln = lt_ekko-ebeln.
```

---

## Real-Time Example

1. Read Purchase Order Numbers from EKKO.
2. Use FOR ALL ENTRIES to fetch all corresponding items from EKPO.

---

## Advantages

* Improves performance
* Reduces database calls
* Faster than SELECT inside LOOP

---

## Interview Questions

### What is FOR ALL ENTRIES?

It is used to retrieve matching records from another table using values stored in an Internal Table.

### What should be checked before using FOR ALL ENTRIES?

Always ensure the Internal Table is **NOT INITIAL**.

```abap
IF lt_ekko IS NOT INITIAL.
```

---

## Common Mistakes

* Using FOR ALL ENTRIES with an empty Internal Table.
* Forgetting the NOT INITIAL check.

---

## Best Practice

Always check whether the Internal Table contains data before using FOR ALL ENTRIES.

---

## Summary

FOR ALL ENTRIES is used to improve database performance by reducing multiple SELECT statements.
