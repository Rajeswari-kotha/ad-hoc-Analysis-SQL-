# ad-hoc-Analysis-SQL
## 1.  Provide the list of markets in which customer  "Atliq  Exclusive"  operates its 
##  business in the  APAC  region.

SELECT distinct market
FROM gdb0041.dim_customer
where region="APAC"
AND customer="Atliq Exclusive"
order by market

![Screenshot 2024-05-28 180109](https://github.com/Rajeswari-kotha/ad-hoc-Analysis-SQL-/assets/162559903/835b79ea-574e-4b6e-af8a-da878ba976de)

## 2.  What is the percentage of unique product increase in 2021 vs. 2020?
 ## The  final output contains these fields, unique_products_2020 ,unique_products_2021 ,percentage_chg 

![Screenshot 2024-05-28 180949](https://github.com/Rajeswari-kotha/ad-hoc-Analysis-SQL-/assets/162559903/29f7d90f-adfc-4ad9-928e-c38166ac8626)

 
