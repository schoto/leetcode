# leetcode
```
select p.product_name, s.year, s.price
from product p
join sales s
on p.product_id = s.product_id
```
```
select unique_id ,name
from employees as emp
left join employeeUNI as uni
on uni.id = emp.id
```
