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
gggg
### Recommendations
