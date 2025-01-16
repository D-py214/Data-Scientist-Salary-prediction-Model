# Data-Scientist-Salary-prediction-Model

## Table of Contents Project 

- Overview
 
- Data Sources
  
- Tools
  
- Data Cleaning and preperation
  
- EDA
  
- Data Analysis
  
- Results
  
- Recommendations
  
- Limitations
  
- Refrences
  


### Overview
The "Data Scientist Salaries Prediction Model" project aims to analyze and predict the salaries of data scientists using machine learning techniques. The project utilizes various data preprocessing, exploratory data analysis (EDA), and modeling techniques to derive insights and build a predictive model. The ultimate goal is to provide a reliable salary prediction tool for aspiring data scientists and organizations looking to benchmark their compensation packages.


### Data Sources
The primary data source for this project is Kaggle, a popular platform for data science competitions and datasets. The dataset used contains information about data scientist salaries, including various features such as experience, education, location, and skills.


### Tools

#### Programming Language

##### Python:

The primary programming language used for data analysis and modeling.
Libraries

-  Pandas: 
For data manipulation and analysis.

-  NumPy:
For numerical operations and handling arrays.

- Matplotlib:
For data visualization.
-  Seaborn:
For statistical data visualization.

-  Scikit-learn:
For machine learning algorithms and evaluation metrics.

-  Statsmodels: 
For statistical modeling and hypothesis testing.

#### Machine Learning Algorithms

-  Linear Regression: For predicting continuous outcomes.
-  Random Forest Regressor: For handling non-linear relationships and feature importance.
-  Gradient Boosting Regressor: For improving prediction accuracy through ensemble learning.

#### Evaluation Metrics

- Mean Absolute Error (MAE): To measure the average magnitude of errors in predictions.
  
- Mean Squared Error (MSE): To measure the average of the squares of the errors.
  
- R-squared (R²): To determine the proportion of variance explained by the model.
  

### Data Cleaning and preperation
Data cleaning and preparation involved several steps:

- Handling Missing Values: Identifying and imputing or removing missing data points.
  
- Data Type Conversion: Ensuring that all features are in the correct format (e.g., converting categorical variables to numerical).
  
- Outlier Detection: Identifying and addressing outliers that could skew the results.
  
- Feature Engineering: Creating new features that could enhance model performance (e.g., extracting years of experience from a date).
  

### EDA
EDA was performed to understand the dataset better and uncover patterns:

- Descriptive Statistics: Summary statistics to understand the distribution of salary and other features.
  
- Correlation Analysis: Identifying relationships between features and the target variable (salary).
  
- Visualizations: Creating plots (e.g., histograms, box plots, scatter plots) to visualize distributions and relationships.

  

### Data Analysis
The analysis involved:

- Feature Selection: Identifying the most relevant features for predicting salaries using techniques like correlation matrices and feature importance from tree-based models.
  
- Model Training: Splitting the dataset into training and testing sets, followed by training various models.
- Hyperparameter Tuning: Optimizing model parameters to improve performance.

### Results
The results of the project indicated that:

- The Random Forest Regressor outperformed other models in terms of prediction accuracy.
  
- Key features influencing salaries included years of experience, education level, and location.
  
- The evaluation metrics showed a low MAE and MSE, indicating a good fit for the model.
  

### Recommendations
Based on the findings, the following recommendations can be made:

- Organizations should consider the identified key features when determining salary packages for data scientists.
  
- Aspiring data scientists should focus on gaining experience and relevant skills to enhance their earning potential.
  
-Future work could involve expanding the dataset to include more geographical regions and job roles.


### Limitations 
The project faced several limitations:

- The dataset may not be representative of all data scientist roles globally.
  
- Potential biases in the data could affect the model's predictions.
  
- The model's performance may vary with new data, necessitating regular updates and retraining.
  

### Refrences 

###### Kaggle Dataset: Data Scientist Salaries

###### Python Libraries Documentation:
       -  Pandas Documentation
       -  NumPy Documentation
       -  Matplotlib Documentation
       -  Seaborn Documentation
       -  Scikit-learn Documentation
       -  Statsmodels Documentation

