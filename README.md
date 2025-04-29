# End-To-End Cricket Data Analysis
## Project objective 

The objective of this project is to perform an end-to-end data analysis of T20 World Cup cricket data with the goal of identifying the best-performing players based on key performance metrics. Using Python, over 500,000+ match records were extracted, cleaned, and analyzed to derive meaningful insights. The project integrates advanced statistical analysis with interactive Power BI dashboards to support player selection, evaluate team performance, and uncover strategic patterns. By combining data engineering and business intelligence, the project enables more accurate, data-driven decision-making in cricket analytics.
## Project Structure 
### Data Collection 
Source: ESPN Cricinfo

Tool Used: Python,Pandas, requests, BeautifulSoup

Scraped detailed match and player statistics from the T20 World Cup 2022.

Extracted data points such as runs, strike rate, wickets, economy, batting/bowling style, etc.
### Data Cleaning and Transformation 
The raw data collected from ESPN Cricinfo was cleaned and transformed using Python (pandas) and Power BI (Power Query).
Converted scraped JSON data to CSV format for easier handling.
Removed duplicates, handled nulls, and standardized data types.
Merged multiple datasets (batting, bowling, match stats) into a single structured file.
Created new performance metrics like Strike Rate, Economy, and Consistency Index.
Imported cleaned CSVs into Power BI and refined them using Power Query.
Established relationships between tables (players, teams, matches) for dynamic filtering.
Final dataset prepared for advanced analysis and interactive dashboarding.



