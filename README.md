# Customer shopping dashboard 🛒🛍️

### Project overview
The Customer Shopping Dashboard project integrates Excel, SQL, and Power BI to deliver in-depth insights into consumer purchasing behaviors. Data from the retail customer table is meticulously extracted and refined using SQL to maintain precision and relevance. Excel aids in preliminary data manipulation and exploratory analysis. Subsequently, Power BI is used to develop an interactive dashboard that visualizes critical metrics, including the total number of customers, average age, purchasing patterns, and sales performance. This cohesive approach promotes data-driven decision-making and enhances the comprehension of customer trends.


![power bi chat](https://github.com/Dimatymadiba/Customer-shopping-dashboard/assets/160989746/34dda12b-5138-4ec3-aa5e-f1d040627d39)


## Data sources
jjjjjj
### Tools used
- Microsoft excel (Data cleaning)
- SQL
- Power BI (Creating dashboard )
### Data cleaning and preparation
#### Using microsoft excel 
##### Step 1: Import data
- Imported raw data into Excel from CSV file.
- Ensured that all data columns were properly formatted .I changed date formates.

 #### Using SQL
##### Step 1: Import Data
- Imported cleaned Excel data into SQL database.
- Used mySQL workbench.
- Used the ```'Import Data'``` wizard to load SQL table .
  
##### Step 2: Handlilng missing Values
- Dealt with any missing value using this query.

 ```sql
 SELECT*
 WHERE column IS NULL;
  ```
  
### Exploratory data analysis
##### Hyothetical Questions asked to come up with the customer behaviour investigation:
- Which month has the highest total quantity of purchases?
- Are there any noticeble trends or seasonal patterns in monthly purchases?
- Which day of the week has the highest total sales for each product categort?
- How do sales for each product category compare pn weekdays versus weekends?
- Which product category has the most consistent sales across all days of the week?
- Which product category has the highest total sales amount for each gender?
- On which day of the week do we see peak sales for each product category and gender?
- How does the sum of quantity and total amount for weekends compare to weekdays for each product category and gender?
### Data analysis
```sql
SELECT count ( "customer ID" )
FROM retail_customer
```
how to get age average
```sql
SELECT AVG(Age) AS average_age
FROM  retail_customer
```


### Results/ analysis findings
Results/Analysis Findings
Peak Purchase Months: Analysis revealed that [insert month] has the highest total quantity of purchases, indicating potential seasonal trends in consumer behavior.

Day-wise Sales Performance: On [insert day of the week], we observed the highest total sales for each product category, suggesting targeted marketing efforts on this day may yield better results.

Gender-based Sales Insights: [Insert product category] emerged as the highest total sales amount for each gender, highlighting potential gender-specific marketing strategies.

Weekday vs. Weekend Trends: Analysis showed variations in sales performance between weekdays and weekends, suggesting the need for tailored promotional activities to leverage these differences effectively.
### Recommendations
Seasonal Campaigns: Develop targeted marketing campaigns during peak purchase months to capitalize on heightened consumer spending.

Day-specific Promotions: Implement promotions and discounts on [insert day of the week] to maximize sales across product categories.

Gender-targeted Marketing: Tailor marketing efforts to align with gender preferences for specific product categories, thereby optimizing sales potential.

Weekday/Weekend Strategies: Devise strategies to leverage weekday and weekend sales trends effectively, such as offering weekday-specific promotions or adjusting inventory levels based on anticipated demand patterns.

Continuous Monitoring: Regularly monitor sales performance and consumer trends to adapt marketing strategies and maintain competitiveness in the market.

By implementing these recommendations, we aim to enhance the effectiveness of marketing initiatives, optimize sales performance, and ultimately drive business growth.





