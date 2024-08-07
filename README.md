# Oskar Andersson Portfolio
Data Analysis / Data Engineering / Data Science

# [Project 1: Waze User Churning Analysis](https://github.com/oreand/data-analyst-portfolio/tree/main/Waze%20Portfolio%20Project) 
* Conducted an in-depth analysis to identify key factors predicting user churn on the app, utilizing Python and various libraries within Jupyter notebooks.
* Cleaned and prepared datasets by identifying and correcting errors, ensuring logical feature relationships, and confirming correct data types for columns.
* Leveraged Pandas, Matplotlib, and Seaborn to aggregate and visually present data during the exploratory data analysis (EDA) stage, analyzing distributions, relationships, and descriptive statistics to provide insights into usage patterns.
* Performed hypothesis testing to determine the statistical significance of device usage on app engagement.
* Engineered new features and developed a Random Forest Classifier model to predict user churn, employing Grid Search to optimize model parameters.
* Enhanced the machine learning model using XGBoost, resulting in a 21% improvement in the F1 score.
* Evaluated the XGBoost model by validating assumptions, generating a confusion matrix, and calculating performance metrics such as accuracy, precision, recall, and F1 scores.

![](/images/feature_importance.PNG)


# [Project 2: Ball Image Classifier](https://github.com/PlayingNumbers/ball_image_classifier) 
For this example project I built a ball classifier to identify balls from different sports. This could be useful for someone who is new to sports from a certain country. They could take a picture of a ball and an app could serve them some information about the history and rules of the game. This is the underlying model for building something with those capabilities. 

I was able to get the model to predict the sport of the ball with 94% accuracy after minimal tuning. For most of the cases this would meet the need of an end user of the app. To get these results I used transfer learning on a CNN trained on resnet34. This created time efficiencies and solid results. 

![](/images/matrix_results.png)
