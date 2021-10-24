# movies_revenues_predictions
# web-scraping-Regression

# Abstract:
The main goal of this project is to predict worldwide Revenue based on features of **IMDb** and **The Number** websites.

# Design:
The project’s goal is to help movie firms determine which movies will result in a high worldwide gross. Movies have many features that may impact their success including a budget, release date, genre and Actor score, and various others. In order to analyze these features, it is first prudent to choose the most transparent resource, which in this case was IMDb and The  Numbers. First, web scrapping is critical to draw data effectively and efficiently. Once data is collected, the next step EDA involved applying pair-plot and heatmap to draw insights from the data. Afterward, it involves using sklearn Linear Regression, Random Forest Regressor Regression, K Neighbors Regression, Decision Tree and Polynomial Regression Models to compare model evaluations based on the result of R-square and Mean Absolute Error.

# Data:
The data that was used in this project is from IMDB and The Numbers.The data of these two website was represented in **10,000 rows** and **51 columns**.
After performing the initial EDA After cleaning the data, we got **1,500 rows** and **10 columns**.

**Target:**
* The Worldwide Revenue

**Features:**
* Budget,
* Domestic Revenue ,
* MPAA Rating,
* Runtime,
* Actor Score,
* Movie age

# Methodology:
**Web Scrapping**
1. Used Beautiful Soup to gather data, starting from one page and using loops to collect data from additional pages

**Base Model**
* Getting simple base model by relevance numerical features Feature Engineering
* Converting categorical features to binary dummy variables
* Adding complexity on base model by adding categorical dummies
* Select the best model among feature engineering
Models: 
* Model 1: Simple linear model
* Model 2: Random Forest Regressor Regression.
* **Model 3: K Neighbors Regression**
* Model 4: Decision Tree
* Model 5: Polynomial linear model (degree 2) 
Model Evaluation and Selection (by comparing validation score & RMSE )

**Final model:** refit K Neighbors Regression model 
* **val score: 0.875927; test score: 0.9014

# Tools:
* Numpy
* Pandas
* Pickle
* Matplotlib
* Seaborn
* Beautiful Soup
* Sklearn
* stats Model
