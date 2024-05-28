## ad-hoc-Analysis-SQL
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

 ## 3. Provide a report with all the unique product counts for each  segment  and 
## sort them in descending order of product counts. The final output contains  2 fields,  segment  ,product_count 


![Screenshot 2024-05-28 181259](https://github.com/Rajeswari-kotha/ad-hoc-Analysis-SQL-/assets/162559903/ae7433cc-0d23-4ec0-965e-8d975676829e)

## 4.Follow-up: Which segment had the most increase in unique products in 
## 2021 vs 2020? The final output contains these fields, segment ,product_count_2020 ,product_count_2021 ,difference 

![Screenshot 2024-05-28 182005](https://github.com/Rajeswari-kotha/ad-hoc-Analysis-SQL-/assets/162559903/154ef6df-b512-4634-b3e2-d45dc65d0bb5)

##  5.  Get the products that have the highest and lowest manufacturing costs. 
## The final output should contain these fields,  product_code ,product ,manufacturing_cost  

![Screenshot 2024-05-28 182035](https://github.com/Rajeswari-kotha/ad-hoc-Analysis-SQL-/assets/162559903/ad0faae8-ff17-42be-8b07-d44bbe60229a)

![Screenshot 2024-05-28 182220](https://github.com/Rajeswari-kotha/ad-hoc-Analysis-SQL-/assets/162559903/5274f87e-3be5-49b5-8882-574990f93514)
 
