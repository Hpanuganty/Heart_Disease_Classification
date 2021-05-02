***This repository will provide a detailed walk through of the 9 essential steps for an end-to-end project*** using the Framingham Heart Study dataset. The data is from an ongoing cardiovascular study on individuals from Framingham, Massachusetts where study participants are monitored for the risk of Coronary Heart Disease (CHD) based off 15 different variables. With this dataset we'll determine the most relevant variables to the outcome and predict the overall risk of being diagnosed with CHD. 

**Step 1: Defining the problem** 
Understanding supervised vs unsupervised ml problems and classification vs regression. In this project the label is provided for us and we're looking to classify individuals into two (binary categories), thus this is a ***supervised classification*** problem

**Step 2: Data Loading**
Brief explanation of common *data loading librarie*s (NumPy, Pandas, Matplotlib, Seaborn), *loading data from a CSV file* and *describing variables/features*

**Step 3: Data Cleaning**
*Identifiying and handling null values* with specific methodologies/techniques 

**Step 4: Exploratory Data Analysis** 
- *Boxplots*: Recognizing and removing outliers (extreme data points) 
- *Heatmaps*: Showcasing the relationship between all variables with the target variable, and tips on reading heatmaps 
- *Distplots*: Showing frequency distribution and skew of each of the variables 
- *Barplots*: Plot relationship between two categorical variables
- *Countplots*: Displaying the count of numerical observations in a categorical 'bin' with bars 
- *Regplots*: Plotting trendline to show relationship between a numerical and categorical variable 

**Step 5: Feature Selection** 
An overview of choosing specific features based off EDA for the ml model and techniques on how to do so. Detailed explanation of ***SelectKBest*** and ***Mutual Information Classification*** methods. 

**Step 6: Data pre-processing** 
Summarize pre-processing steps including *train-test split*, *feature scaling* and *balancing via SMOTE*

**Step 7: Predictive Modeling** 
Walk through of 4 common ***classification algorithms*** and reasoning as to why it was used 
- *Logistic Regression*: Understanding influence of one or more indepedent variables to single outcome variable
- *Random Forest*: Combines multiple decision trees into one model, enhancing performance of each tree model into one strong tree model 
- *K-Nearest Neighbors*: Calculating 'closeness' between each data point to assign the label 
- *Support Vector Machine*: Linear separator to divide data points into classes 

**Step 8: Hyperparameter Tuning** 
Discussed importance of hyperparameter tuning, overview of RandomizedSearch/GridSearch and provided an explanation as to how hyperparameters were adjusted for each model and how tuning affected overall model performance. 

**Step 9: Model Evaluation** 
Explored the different ways of evaluating a model and why ***accuracy/confusion matrices*** were chosen in this instance. Provided reasoning as to why ***Hypertuned Random Forest*** was the model that represented the dataset and outcome the best. 

[![model-ranking.jpg](https://i.postimg.cc/13B4m2Lm/model-ranking.jpg)](https://postimg.cc/ts19DSqw)
