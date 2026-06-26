# JOINS in SAP ABAP

## Definition

JOIN is used to retrieve related data from two or more database tables in a single SELECT statement.

---

## Types of JOIN

### INNER JOIN

Returns only matching records from both tables.

### LEFT OUTER JOIN

Returns all records from the left table and matching records from the right table.

### RIGHT OUTER JOIN

Returns all records from the right table and matching records from the left table.

---

## Example

```abap
SELECT a~ebeln,
       a~lifnr,
       b~matnr,
       b~menge
  FROM ekko AS a
  INNER JOIN ekpo AS b
    ON a~ebeln = b~ebeln
  INTO TABLE lt_output.
```

---

## Real-Time Example

Join **EKKO** (Purchase Order Header) and **EKPO** (Purchase Order Item) to display Purchase Order Number, Vendor, Material, and Quantity.

---

## Interview Questions

### Why do we use JOIN?

To retrieve related data from multiple tables efficiently.

### Which JOIN is most commonly used?

INNER JOIN.

---

## Common Mistakes

* Incorrect JOIN condition.
* Joining unnecessary tables.

---

## Best Practice

Use JOIN instead of nested SELECT statements whenever possible.

---

## Summary

JOIN improves performance by retrieving related data from multiple tables in a single database call.
