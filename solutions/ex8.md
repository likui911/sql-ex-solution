**Exercise: 8**

Find the makers producing PCs but not laptops.

**Solution**

```sql
SELECT DISTINCT maker
FROM product
WHERE type = 'PC'
EXCEPT
SELECT DISTINCT maker
FROM product
WHERE type = 'laptop'

```
