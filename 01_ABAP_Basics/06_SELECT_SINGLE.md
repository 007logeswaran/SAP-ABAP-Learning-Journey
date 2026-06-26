# SELECT SINGLE in SAP ABAP

## Definition

SELECT SINGLE retrieves only one record from a database table.

---

## Syntax

```abap
SELECT SINGLE *
  FROM ekko
  INTO ls_ekko
  WHERE ebeln = lv_ebeln.
```

---

## Real-Time Example

```abap
DATA: ls_ekko TYPE ekko.

SELECT SINGLE *
  FROM ekko
  INTO ls_ekko
  WHERE ebeln = '4500000010'.
```

---

## Difference

| SELECT                     | SELECT SINGLE             |
| -------------------------- | ------------------------- |
| Retrieves multiple records | Retrieves only one record |
| Uses Internal Table        | Uses Work Area            |

---

## Interview Questions

### When do we use SELECT SINGLE?

When only one record is required using a unique key.

### Why use SELECT SINGLE?

It improves performance by retrieving only one record.

---

## Common Mistakes

* Using SELECT SINGLE without a proper WHERE condition.
* Expecting multiple records from SELECT SINGLE.

---

## Best Practice

Always use a primary key in the WHERE clause.

---

## Summary

SELECT SINGLE is used to fetch exactly one record from a database table.
