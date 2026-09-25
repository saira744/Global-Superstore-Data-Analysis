\# Global Superstore Data Analysis



\## Project Overview



This project analyzes the Global Superstore dataset to understand sales, profit, customers, products, markets, regions, and overall business performance.



The project follows an end-to-end data analytics workflow using Python, SQL Server, and Power BI.



\## Tools \& Technologies



\- Python

\- Jupyter Notebook

\- SQL Server

\- Power BI

\- Docker



\## Project Workflow



Raw CSV Data  

↓  

Python / Jupyter  

(Data Cleaning \& Validation)  

↓  

Clean Dataset  

↓  

SQL Server  

(Database Design \& Business Analysis)  

↓  

Power BI  

(Dashboard \& Visualization)



\## 1. Data Cleaning \& Validation



Python and Jupyter Notebook were used to inspect and prepare the dataset.



The following checks were performed:



\- Missing values

\- Duplicate records

\- Data types

\- Date validity

\- Quantity values

\- Extra spaces

\- Data consistency

\- Basic data quality checks



After cleaning and validation, the dataset contained:



\- 51,290 rows

\- 26 columns



The cleaned dataset was saved as `superstore\_clean.csv`.



\## 2. SQL Server Database



The cleaned dataset was imported into SQL Server and organized into relational tables.



Main tables:



\- Customers

\- Orders

\- OrderDetails

\- Products



Relationships were established between the tables to support relational analysis.



SQL was then used to perform business analysis using:



\- JOINs

\- GROUP BY

\- HAVING

\- Subqueries

\- CTEs

\- CASE statements

\- Window functions

\- RANK()

\- LAG()

\- Running totals

\- Month-over-month analysis



\## 3. Business Analysis



The analysis covered several business questions, including:



\- What are the total sales and total profit?

\- How many orders were placed?

\- What is the overall profit margin?

\- How do sales and profit vary by year?

\- Which categories generate the most sales and profit?

\- Which subcategories generate the most profit?

\- How do different markets perform?

\- Which customers generate the highest sales?

\- Which customers and products generate losses?

\- How does discount level relate to profitability?

\- Which countries and regions have stronger or weaker performance?

\- How does shipping cost vary by shipping mode?

\- How do sales change month by month?

\- Which customers are repeat customers?



\## 4. Key Business Metrics



| Metric | Value |

|---|---:|

| Total Sales | 12,642,905.00 |

| Total Profit | 1,467,456.55 |

| Total Orders | 25,035 |

| Profit Margin | 11.61% |

| Total Records | 51,290 |



\## 5. Power BI Dashboard



Power BI was used to create an interactive dashboard for business reporting and visualization.



The dashboard includes:



\- Total Sales KPI

\- Total Profit KPI

\- Total Orders KPI

\- Profit Margin KPI

\- Sales \& Profit Trend by Year

\- Sales \& Profit by Category

\- Profit by Subcategory

\- Sales by Market



Interactive slicers were also added for:



\- Year

\- Region

\- Segment



\## 6. Key Findings



\- Total sales were approximately 12.64 million.

\- Total profit was approximately 1.47 million.

\- Overall profit margin was approximately 11.61%.

\- Technology generated the highest sales among the three main categories.

\- Furniture had a lower profit margin compared with Technology and Office Supplies.

\- Tables were a loss-making subcategory in the analysis.

\- Sales increased from 2011 to 2014.

\- Different markets showed significant differences in sales and profitability.

\- Higher discount levels were generally associated with weaker profitability in the analyzed data.



\## 7. Project Files



```text

Global-Superstore-Data-Analysis

│

├── data

│   └── clean

│       └── superstore\_clean.csv

│

├── notebooks

│   └── Superstore\_Analysis.ipynb

│

├── powerbi

│   └── Superstore\_Dashboard.pbix

│

├── docker-compose.yml

├── .gitignore

└── README.md



8\. Docker



Docker was used as supporting infrastructure to run SQL Server in a local container environment.



The Docker configuration helped provide a consistent local SQL Server environment for the project.



Conclusion



This project demonstrates an end-to-end data analytics workflow, starting from raw data cleaning and validation, followed by relational database design and SQL-based business analysis, and finally interactive reporting and visualization in Power BI.

