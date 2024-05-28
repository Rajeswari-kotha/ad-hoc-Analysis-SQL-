# ad-hoc-Analysis-SQL
1.  Provide the list of markets in which customer  "Atliq  Exclusive"  operates its 
business in the  APAC  region.

SELECT distinct market
FROM gdb0041.dim_customer
where region="APAC"
AND customer="Atliq Exclusive"
order by market
