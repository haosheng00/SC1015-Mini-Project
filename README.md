# _'Robo-Medivisor'_ Heart Disease Prediction
SC1015 Introduction to Data Science and Artificial Intelligence Mini-Project

## About
Acknowledging the severity of heart disease and the benefits of its early detection, our group aims to predict the possibility of individuals contracting heart disease with the use of a [dataset retrieved from IEEE](https://ieee-dataport.org/open-access/heart-disease-dataset-comprehensive#files). With the best machine learning model selected, our 'Robo-Medivisor' will analyse this possibility with predictor variables taken from the patients' medical check-ups and recommend them for more comprehensive check-ups. It will also alert and send doctors the patients' health report if required.

## Contributors
- Koh Hao Sheng ([@haosheng00](https://github.com/haosheng00)) - Data Preparation, Exploratory Data Analysis (EDA), Machine Learning Models (Decision Tree and Random Forest), Solution, Slides, GitHub README
- Lee An Ni ([@3Clovers](https://github.com/3Clovers)) - Data Preparation, Exploratory Data Analysis (EDA), Machine Learning Models (Logistic Regression), Solution, Slides, GitHub README
- Sim Guanyu ([@cooliomoolio1108](https://github.com/cooliomoolio1108)) - Motivation, Data Visualization, Evaluation, Solution, Slides

## Table of Contents
1. [Motivation and Problem Statement](https://github.com/haosheng00/SC1015-Mini-Project#motivation-and-problem-statement)
2. [Models Used](https://github.com/haosheng00/SC1015-Mini-Project#models-used)
3. [Data Preparation](https://github.com/haosheng00/SC1015-Mini-Project#data-preparation)
4. [Exploratory Data Analysis (EDA)](https://github.com/haosheng00/SC1015-Mini-Project#exploratory-data-analysis-eda)
5. [Machine Learning Models](https://github.com/haosheng00/SC1015-Mini-Project#machine-learning-models)
6. [Conclusion](https://github.com/haosheng00/SC1015-Mini-Project#conclusion)
7. [Learning Points](https://github.com/haosheng00/SC1015-Mini-Project#learning-points)
8. [References](https://github.com/haosheng00/SC1015-Mini-Project#references)

## Motivation and Problem Statement
**_Heart disease_** is the leading cause of death, accounting for 32% of all deaths in the world. Given the severity of the situation, our group wants to reduce the implications of heart disease with early detection and intervention which allows for the best chance for successful treatment and survival.
- How can we assist doctors to speed up the diagnosis of heart disease to minimise further implications? 
- Which model is the best in predicting heart disease to aid in our goal of early detection?

## Models Used
- Decision Tree
- Random Forest
- Logistic Regression

## Data Preparation
- Imported the dataset, Separated numeric and categorical variables in different data frames
- Renamed a variable for easier visualisation in EDA
- Removed anomalies for higher precision and accuracy
- Ensured dataset is balanced

## Exploratory Data Analysis (EDA)
- Analysed single and multi-variate statistics of numeric variables through the use of box plots, scatter plots, strip plots, histograms, pairplot, correlation table and heatmap
- Heatmaps used for categorical variables
- Extracted the relevant predictor variables from data-driven insights

## Machine Learning Models
- 3 models used, namely Decision Tree, Random Forest and Logistic Regression
- Adjusted 2 major hyper-parameters for Random Forest, depth and estimators, to raise the classifiction accuracy of the model
- Logistic Regression was done twice in order to make a comparison between extracted dataframe and a dataframe with all predictor variables with back elimination

## Conclusion
- Random Forest with adjusted hyper-parameters returns the highest accuracy (93%) among the 3 models used, hence it is the best model
- Extracted dataframe from data-driven insights is a better model fit (higher R-squared value) compared to dataframe with all predictor variables for Logistic Regression
- Identified signficant predictor variables using p-value from Logistic Regression
- Correlation between predictor variables can be low among each other but can be significant to the presence of heart disease

## Learning Points
- GitHub Collaboration
- New Machine Learning Models (Random Forest, Logistic Regression)
- Soft Skills such as Design Thinking to utilise models efficiently and effectively

## References
- https://ieee-dataport.org/open-access/heart-disease-dataset-comprehensive#files
- https://www.who.int/news-room/fact-sheets/detail/cardiovascular-diseases-(cvds)#:~:text=Cardiovascular%20diseases%20(CVDs)%20are%20the,%2D%20and%20middle%2Dincome%20countries
- https://www.myheart.org.sg/health/heart-disease-statistics/#:~:text=Singapore%20Statistics,to%20heart%20diseases%20or%20stroke
- https://scholar.smu.edu/cgi/viewcontent.cgi?article=1041&context=datasciencereview
- https://www.analyticsvidhya.com/blog/2021/06/understanding-random-forest/#:~:text=Random%20forest%20is%20a%20Supervised,average%20in%20case%20of%20regression


## *Special Thanks to our Teaching Assistant Sun Chenyu for your guidance throughout the project and Course Instructors Associate Professor Bo An and Dr Sourav Sen Gupta for teaching the relevant content.*
