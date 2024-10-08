# Oskar Andersson's Data Science Portfolio
Data Analysis / Data Science / Data Engineering

# [Project 1: Waze User Churning Analysis](https://github.com/oreand/data-analyst-portfolio/tree/main/Waze%20Portfolio%20Project) 
* Conducted an in-depth analysis to identify key factors predicting user churn on the app, utilizing Python and various libraries within Jupyter notebooks.
* Cleaned and prepared datasets by identifying and correcting errors, ensuring logical feature relationships, and confirming correct data types for columns.
* Leveraged Pandas, Matplotlib, and Seaborn to aggregate and visually present data during the exploratory data analysis (EDA) stage, analyzing distributions, relationships, and descriptive statistics to provide insights into usage patterns.
* Performed hypothesis testing to determine the statistical significance of device usage on app engagement.
* Engineered new features and developed a Random Forest Classifier model to predict user churn, employing Grid Search to optimize model parameters.
* Enhanced the machine learning model using XGBoost, resulting in a 21% improvement in the F1 score.
* Evaluated the XGBoost model by validating assumptions, generating a confusion matrix, and calculating performance metrics such as accuracy, precision, recall, and F1 scores.

![](/images/feature_importance.PNG)

# [Project 2: Football Statistics SQL Analysis](https://github.com/oreand/data-analyst-portfolio/tree/main/Football%20Portfolio%20Project)
*	Conducted comprehensive analysis on over 2,000,000 data points from Europe's top football leagues, utilizing a locally hosted PostgreSQL server to efficiently store, organize, and query the large dataset.
* Designed database schemas with optimized table structures, incorporating primary and foreign keys to enhance query performance by up to 20%, and developed strategic SQL queries to ensure data integrity post-loading.
*	Crafted complex queries using aggregate functions, HAVING() and joins to identify top players by goal contributions.
*	Developed advanced SQL queries to rank clubs by wins and overall win rate, using CASE statements and Common Table Expressions (CTEs) to analyze win rate variations between home and away games, providing insights across 60,000+ matches.
*	Engineered SQL queries to examine player birthplaces, culminating in an in-depth analysis comparing goals scored by country of birth versus country of citizenship, leveraging CTEs to uncover insights on which countries produce and retain top offensive talent.

![](/images/win_rate_difference.PNG)

# [Project 3: Last.fm Artists Data Exploration](https://github.com/oreand/data-analyst-portfolio/tree/main/Artists%20Portfolio%20Project) 
* Developed an ETL pipeline using Python to call the Last.fm API for data on musical artists, using SQL to clean and enhance the structure of the data, facilitating seamless integration into Tableau for effective visualization.
* Established and configured a local MySQL server to effectively facilitate the storage and administration of the acquired dataset.
* Effectively converted the obtained data into a CSV file format and efficiently uploaded it to the local MySQL server, enabling streamlined data handling and subsequent querying via Visual Studio Code.
* Applied strategic SQL queries to clean the dataset, encompassing operations such as the removal of duplicate rows, manipulation of data types within columns, and proficient string manipulations, thereby ensuring the optimization of data quality and integrity.
* Formulated SQL queries to address inquiries concerning the dataset, utilizing an array of aggregate functions to derive insightful conclusions and actionable insights, consequently enriching the overall understanding of the dataset's characteristics and trends.

#[Artists Tableau Link](https://public.tableau.com/authoring/ArtistsPortfolio/ListenerandPlaycountRankings#1)
