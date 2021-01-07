**Exercise: 9**

Find the makers of PCs with a processor speed of 450 MHz or more. 

Result set: maker.

**Solution**

```sql
SELECT DISTINCT maker
FROM Product
	LEFT JOIN PC ON Product.model = PC.model
WHERE PC.speed >= 450
```
