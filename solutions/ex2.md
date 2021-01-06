**Exercise: 2**

List all printer makers. 

Result set: maker.

**Solution**

```sql
SELECT DISTINCT p1.maker
FROM Product p1
WHERE p1.type = 'printer'
```
