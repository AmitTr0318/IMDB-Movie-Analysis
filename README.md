# IMDB-Movie-Analysis
**Investigation using Data Analytics skills on which factors influence the success of a movie on IMDB**

Analyzed a comprehensive IMDb movie dataset using SQL and R to uncover insights into box office performance, ratings, and genre trends. Conducted extensive data cleaning and preparation in MySQL to ensure accuracy, then applied linear and non-linear regression models in R to identify correlations between variables like budget, runtime, and audience ratings. The analysis provided actionable insights on factors impacting movie success, supporting data-driven decisions in content and production planning.

[Google Sheet Link](https://docs.google.com/presentation/d/1QuDumlZAwJw3Av4q6z0psOMCY9wRF0olIxrr94UJdKM/edit?usp=sharing)

Tech Stack used:
***SQL
*Excel
*R Programming**

Business Question:
- Which factors influence the success of movies on IMDB?

Steps implemented:

Data Cleaning:
-Handle missing values, remove duplicates,outlier detection, and standardize formats for fields like dates and genres.
-Remove irrelevant columns or rows to focus on key analysis variables (e.g., budget, runtime, ratings).

Database Setup in MySQL:
-Use the LOAD DATA INFILE command to upload the cleaned data into MySQL.
Example command:
**LOAD DATA INFILE 'path/to/yourfile.csv'
INTO TABLE imdb_movies
FIELDS TERMINATED BY ',' 
LINES TERMINATED BY '\n' 
IGNORE 1 LINES;**

Exploratory Data Analysis (EDA) in SQL:
-Ran SQL queries to generate descriptive statistics (e.g., average ratings, distribution of genres).

Statistical Analysis in R
-Export data from MySQL to R for statistical analysis and modeling.
-Run linear regression to explore relationships between numerical variables (e.g., budget vs. revenue).
-Apply non-linear regression models if relationships are complex or non-linear, for instance, using polynomial regression.
-Evaluate model accuracy using metrics like R-squared, Mean Absolute Error (MAE), or Root Mean Squared Error (RMSE).
-Interpret results to identify key factors impacting movie success.

Insights & Reporting:
-Summarize key findings from regression analyses and EDA, identifying influential variables.
-Create charts and visual summaries to highlight trends or important relationships, using tools like Power BI, Tableau, or R visualization libraries.



