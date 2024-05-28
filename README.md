## ad-hoc-Analysis-SQL

# Atliq Hardwares, a fictional company, is a major computer hardware maker in India and abroad. Yet, they lack quick insights for smart decisions. So, a SQL challenge is on the horizon to fill this data gap.

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

##  6.Generate a report which contains the top 5 customers who received an average high 
## pre_invoice_discount_pct  for the  fiscal  year 2021  and in the 
## Indian  market. The final output contains these fields, customer_code ,customer ,average_discount_percentage

![Screenshot 2024-05-28 182313](https://github.com/Rajeswari-kotha/ad-hoc-Analysis-SQL-/assets/162559903/c255cb56-cbbd-4526-93c1-d7c5f38868ff)

## 7 Get the complete report of the Gross sales amount for the customer  “Atliq Exclusive”  for each month  .
 ## This analysis helps to  get an idea of low and  high-performing months and take strategic decisions. 
## The final report contains these columns: Month ,Year ,Gross sales Amount

![Screenshot 2024-05-28 182527](https://github.com/Rajeswari-kotha/ad-hoc-Analysis-SQL-/assets/162559903/dc15ee10-90ee-49e1-8feb-89d0e0b5dcf1)

## 8. In which quarter of 2020, got the maximum total_sold_quantity? The final 
## output contains these fields sorted by the total_sold_quantity,  Quarter , total_sold_quantity

![Screenshot 2024-05-28 182607](https://github.com/Rajeswari-kotha/ad-hoc-Analysis-SQL-/assets/162559903/513f0ad0-8b81-479c-8ac6-ea5e081ab4a4)

## 9. Which channel helped to bring more gross sales in the fiscal year 2021 
## and the percentage of contribution?  The final output  contains these fields, channel ,gross_sales_mln  percentage 

![Screenshot 2024-05-28 182649](https://github.com/Rajeswari-kotha/ad-hoc-Analysis-SQL-/assets/162559903/2cd574cd-1c29-4d59-8b8c-bece401ac6a4)

## 10. Get the Top 3 products in each division that have a high 
## total_sold_quantity in the fiscal_year 2021? The final output contains these  fields, division ,product_code

![Screenshot 2024-05-28 182658](https://github.com/Rajeswari-kotha/ad-hoc-Analysis-SQL-/assets/162559903/b9745035-da6a-4921-bd03-7b7a64fbc9fc)

 
