
## 1. PROBLEM STATEMENT 
Hiring and retaining employees require capital, time and skills. In the US, firms face an average churn of about 10%-15%, and this churn can prove costly. It is estimated that an unwanted departure of an employee can cost the firm anywhere from 30% (of his/her annual salary) for more junior employees to 400% for much more senior employees. The difficulty of finding a replacement and bringing that replacement to the same level of productivity, the lost knowledge and know-how, and the period where resources have to carry the extra load of a missing colleague can be serious problems, especially for firms that face a higher rate of attrition.

Understanding the reasons and anticipating when an employee is most likely to leave could lead to take preventive actions and planning new hirings in advance, reducing the costs above mentioned. To do so, HR has collected extensive historical data on their employees, such as age, gender, job satisfaction, environment satisfaction, education field, job role, income, overtime, percentage salary hike, tenure, training time, years in current role, relationship status, and more.HR is also providing a variable (attrition) that indicates if the employee left the company or not.

## 2. SUMMARY OF THE PROJECT

Exploratory Data Analysis to find differences between the group of employees that stayed and the ones that left and to identify the variables that most significantly impact the attrition.

Development of three binary classifiers (linear regressor classifier, random forest, neural network) to predict if an employee will stay or will leave. Gridsearch used to tune the hyperparameters. Since the data set is imbalanced (85% /15% split btween majority and minority class), some sampling techniques (Random Over Sampling, SMOTE) are utilized.

## 3. DATA
Original data was published in IBM but was removed. The dataset is still available in [Kaggle](https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset)

## 4. FOLDER STRUCTURE
- Data
  -  \raw: contains the original data set.
  -  \processed: contains cleaned and preprocessed files
- src: contains the notebooks

## 5. NOTEBOOK STRUCTURE
The repository contains a total of six (6) notebooks:
- *1. Data description and initial intuitions*: structure and characteristics of the data set (rows, columns, missing values...), field description and initial suposition/guesses prior to the analysis
- *2. EDA*: exploratory data analysis, subdivided in categorical variable and numerical variable.
- *3. Data cleaning and preprocessing*: application of One Hot Encoder and scaling.
- *4. Model*: train and test a logistic regression classifier, random forst classifier and a neural network. Includes hyper farameter tunning (Gridsearch) and sampling techniques.
- *5. Conclussuions and recommendations*: summary of the analysis and findings.
- *Full-Employee churn*:five previous notebooks consolidated.
