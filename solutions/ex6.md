**Exercise: 6**

For each maker producing laptops with a hard drive capacity of 10 Gb or higher, find the speed of such laptops. 

Result set: maker, speed.

**Solution**

```sql
SELECT DISTINCT Product.maker, Laptop.speed
FROM Product
	RIGHT JOIN Laptop ON Product.model = Laptop.model
WHERE Laptop.hd >= 10;
```
