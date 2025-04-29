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
### DashBoard Building
An interactive Power BI dashboard was created to explore and visualize performance metrics from the T20 World Cup 2022 dataset.
Role-based player analysis: Power Hitters, Anchors, Finishers, All Rounders, and Specialist Fast Bowlers

KPIs for each role including:

Batting Average, Strike Rate, Economy, Wickets, and Bowling Strike Rate

Dynamic visuals like:

Line charts for batting & bowling trends

Bubble chart to compare Strike Rate vs Batting Average

Slicers for filtering by stage (Qualifier/Super 12), player name, and role

Clean, dark-themed layout for better contrast and readability
#### Dashboard Preview:
This dashboard empowers analysts and fans to identify impactful players, uncover strategic trends, and make data-informed selections for the best playing XI
### Key Insights
Finishers (Stoinis, Maxwell) excelled with strike rates above 160.

Sikandar Raza was a strong all-rounder.

Pandya showed strong bowling despite a lower strike rate.

Bowling strike rate and economy predicted match outcomes better than wickets.

The Best XI matched teams that reached later stages.

Teams with balanced batting roles won more often.
### Technologies Used 
Programming Languages: Python

Libraries: pandas, BeautifulSoup

Data Visualization: Power BI

Web Scraping: requests, BeautifulSoup

IDE: Jupyter Notebook

Data Storage: CSV (for cleaned data)

Tools: Power Query (for data transformation in Power BI)








