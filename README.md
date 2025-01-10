# Introduction
HIV is one of the chronic diseases that is associated with high mortality and morbidity despite the invention of new ART medicines. Especially the patients in immunocompromised or in the Chronic stage are more prone to death than those in the acute stage of the disease. 
Therefore predicting the mortality at this stage will prevent the disease progression to AIDS and chances of succumbing to death. Most of the studies used statistical methods to predict the mortality and only few studies used DL and ML this led me to use ML to predict the mortality. 
This is a binary classification problem that identifies patients died from the survived.

# Method
The whole prediction task has been done in following steps:
### 1. Data collection
The dataset was collected from UCI machine learning repository and the link for the dataset is here: 

### 2. Data preprocessing
This includes data transformation, outlier detection and treatment

### 3. Exploratory data analysis
Univariate analysis was done to understand the data distribution in each variable, 
Bivariate analysis was done to understand the relationship between each variable. 
Multivariate analysis was done to understand the correlation and relationship of other variables with the target variable

### 4. Feature engineering
This included data balancing using SMOTE, one-hot encoding, Min max scaling, Recursive feature elimination was used to choose the important variables. 

### 5. Model selection and model building
Logistic regression, Random forest, Support Vector Machine, & XG Boost were chosen since they performed well in other mortality prediction studies. 

### 6. Hyperparameter tuning
Gridsearch and Randomized search were used with 5 fold cross validation 

### 7. Model evaluation
All the models were evaluated using Accuracy, Precision, recall, confusion matrix, and AUC-ROC score 

The best performing model and the predictors of mortality were visualized to know their importance. 
