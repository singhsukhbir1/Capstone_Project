# [Housing_Price_Predictions](https://github.com/singhsukhbir1/Housing_Price_Predictions)
# Purpose
The main purpose of this analysis is to create a machine learning model in order to predict the prices of houses based on multiple features for example: number of bedrooms, lot size, neighborhood, area etc. Our goal for this project is to build an end-to-end machine learning model that is able to predict house prices better than individuals. We would love to implement our models in real-life situations and assist future house buyers in making advised decisions and help real estate agents attain more sales by providing quality information. We want to use our model to evaluate the value of homes within a timeframe of 6-12 months. There are many outside factors that could contribute to the decline/rise in house prices (i.e Covid-19, Financial Crisis), which is why we want to limit the timeframe. For future purposes. we could use the results that we obtain from our project and see if there are any ways that we can extend our timeframe while maintaining efficiency and accuracy. 

A few questions we are looking to answer are:
1. What attributes of a house are highly/inversely correlated with the price of the house? What insights could we determine from these attributes? 
2. Will our test house price match the actual retail value of a home? 
3. Are there any missing attributes that might contribute to better results in this model, that the current dataset might be missing? 
4. What ways can we finetune the dataset that we currently have and how will this impact our efficiency of our model?


# Managing GitHub Repository
- Created the repository and added all the members.
- A README.md file is added and the repository is set to Public view.
- Purpose or analysis and roles of members are updated.
---
---

# Incharge of the mockup database
- I have downloaded the dataset from kaggle and created the dataframe using pandas library in jupyter notebook. In addition to this I have created a data pipeline to connect to the database sever using SQL.The dataset includes 78 columns.


---
# Building Machine Learning Models
---
---

## Building Machine Learning Models: 
	
## Shallow Learning: 
- It would be a good idea to start the Machine Learning component by examining a simpler rule-based algorithm 
  
-    We can predict our response variable, by using the following regressors: Linear Regressor, DecisionTreeRegressor & RandomForest Regressor 

-	Based off of our understanding, my belief is that Random Forest will produce the best results as it is the ensemble of Decision Trees. Ensemble models in general produce better results than singular models 

---

### Linear Regression: 
---
#### Advantages: 

(1) Simple to Implement: 

- it is less complex in comparison to other algorithms when you are knowing the relationship between the dependent and independent variable 

(2) Performance on linearly seperable datasets: 

(3) We can reduce overfitting 

- Using Dimensionality Reduction Techniques
- Regularization Techniques
- Cross-Validation 


#### Disadvantages: 

(1) Prone to Underfitting:

- has difficulty with complex datasets and poor-quality data 
- must have proper pre-processing performed on the data prior to analyzing 


(2) Sensitive to outliers:

- if there are more than a few outliers in comparison to non-outliers it can skew the true relationship

(3) Assumes Linearity:

- linear relationship between dependent and independent variables is considered to be a straight-line relationship 
- assumes independence between attributes


---
### Multiple Regression: (more than one independent variable) 
---

#### Advantages: 


(1) the ability to determine the relative influence of one or more predictor variables to the target variable

- example: the size of home and number of bedrooms have a strong correlation to the price of the home, while proximity to school has no correlation at all 

(2) Ability to find Outliers: 

(3) Broader Type of Regression: 

- it can handle straight line and non-linear regression with multiple explanatory variables 


#### Disadvantages: 

(1) Sensitive to the Data being used 

- Incomplete/Minimal/Error data can lead to the conclusion that a correlation is a causation 

![LRvsMLR](https://i.ibb.co/55vj4ym/SLR-vs-MLR.png)


---
### Decision Trees
---
 
#### Advantages: 

(1) Easy to Interpret: 

- the hierarchical decision-making process allows for the reader to understand which attributes are most important

(2) We barely require data, as it can handle a variety of data types:

- Discrete 
- Continuous 
- Continuous variables converted into Categorical values

(3) Flexible:

- can be used for classification and regression tasks. 
- even if attributes are or are not closely related, as the algorithm will make one of two choices. 

#### Disadvantages:

(1) Prone to Overfitting:

- The more complex the decision tree is the more likely it will overfit 

(2) High Variance Estimators:

- small variations within our attributes can lead to a completely different tree 

(3) Costly:

- they can be more costly to train in comparison to other algorithms 

---
### Random Forest Regressor: 
---

#### Advantages:

(1) Minimalizes the Overfitting: 
- in decision trees overfitting was a disadvantage, however by  reducing this we can help improve the accuracy 

(2) Data Cleaning is reduced
- we can automate missing values in the dataset we have 
- we do not need to normalize our as it follows a rule-based approach 

#### Disadvantages: 

(1) Power and Resources:
- we need strong computational power, as it builds numerous trees and combines their outputs 

(2) Time Consuming:
- due to combining a lot of decision trees we would need a more time for training 

![SDTvsRF](https://i.ibb.co/0mZJkTW/DT-vs-RF.png)

---
---
# Deciding the technologies
---
---

## Technologies Used
What will be used for each section?  
-  Data cleaning
	- Jupyter Notebook
	- pandas
-  DataBase Storage 
	- PostgreSQL
	- SQLite
-  Machine Learning
	- Logistic Regression (LR)
		- Jupyter Notebook
		- R
- Dashboard
	- Javascript, d3.json
  	- CSS
  	- HTML

## Data cleaning
Pandas will be used to clean the data and perform an exploratory analysis. Further analysis will be completed using Jupyter Notebook. 
![This is an image](https://github.com/singhsukhbir1/Housing_Price_Predictions/blob/main/Resources/data%20%20cleanning.png?raw=true)
![This is an image](https://github.com/singhsukhbir1/Housing_Price_Predictions/blob/main/Resources/data%20%20cleanning2.png?raw=true)
![This is an image](https://github.com/singhsukhbir1/Housing_Price_Predictions/blob/main/Resources/data%20%20cleanning3.png?raw=true)

## Database Storage
PostgreSQL or SQLite depending operations efficiently.
The SQLite system supports in-memory capabilities that help to perform the data operations efficiently, whereas, in the PostgreSQL system, there is no such functionality of in-memory capability. The SQLite system does not support any partitioning methods.
![This is an image](https://github.com/singhsukhbir1/Housing_Price_Predictions/blob/main/Resources/data%20storage.png?raw=true)

## Machine Learning Model
We will test various machine learning models to determine the best model for predictions.
1. Linear Regression
2. Regression
3. Decision Trees
4. Random Forest Regression

## Dashboard
Using Javascript, HTML, CSS for building the webpage.  


Contribution: 
## Square: Sukhbir Singh 
## Triangle:  Nishan Manoharan 
## Circle: Jagbir Singh 
## X: Chenglu Yang
