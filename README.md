# ad-hoc-Analysis-SQL
1.  Provide the list of markets in which customer  "Atliq  Exclusive"  operates its 
business in the  APAC  region.

SELECT distinct market
FROM gdb0041.dim_customer
where region="APAC"
AND customer="Atliq Exclusive"
order by market

![](C:\Users\91807\Pictures\Screenshots\Screenshot 2024-05-28 180109.png)
