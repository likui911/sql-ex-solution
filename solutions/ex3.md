**Exercise: 3**

Find the model number, RAM and screen size of the laptops with prices over $1000.

**Solution**

```sql
SELECT model, ram, screen
FROM laptop
WHERE price > 1000
```
