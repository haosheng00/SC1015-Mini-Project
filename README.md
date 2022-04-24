# '_Robo-Medivisor_' Heart Disease Prediction
SC1015 Introduction to Data Science and Artificial Intelligence Mini-Project

## About
Acknowledging the severity of heart disease and the benefits of its early detection, our group aims to predict the possibility of individuals contracting heart disease with the use of a [dataset retrieved from IEEE](https://ieee-dataport.org/open-access/heart-disease-dataset-comprehensive#files). With the best machine learning model selected, our 'Robo-Medivisor' will analyse this possibility with predictor variables taken from the patients' medical check-ups and recommend them for more comprehensive check-ups. It will also alert and send doctors the patients' health report if required.

## Contributors
- Koh Hao Sheng ([@haosheng00](https://github.com/haosheng00)) - Data Preparation, Exploratory Data Analysis (EDA), Machine Learning Models (Decision Tree and Random Forest), Solution, Slides
- Lee An Ni ([@3Clovers](https://github.com/3Clovers)) - Data Preparation, Exploratory Data Analysis (EDA), Machine Learning Models (Logistic Regression), Solution, Slides, GitHub README
- Sim Guanyu ([@cooliomoolio1108](https://github.com/cooliomoolio1108)) - Motivation, Data Visualization, Evaluation, Solution, Slides

## Table of Contents
1. [Motivation and Problem Statement](https://github.com/haosheng00/SC1015-Mini-Project/edit/main/README.md#motivation-and-problem-statement)
2. [Models Used](https://github.com/haosheng00/SC1015-Mini-Project/edit/main/README.md#models-used)
3. [Data Preparation](https://github.com/haosheng00/SC1015-Mini-Project/edit/main/README.md#data-preparation)
4. [Exploratory Data Analysis (EDA)](https://github.com/haosheng00/SC1015-Mini-Project/edit/main/README.md#exploratory-data-analysis-eda)
5. [Machine Learning Models](https://github.com/haosheng00/SC1015-Mini-Project/edit/main/README.md#machine-learning-models)
6. [Reflection](https://github.com/haosheng00/SC1015-Mini-Project/edit/main/README.md#reflection)
7. [Learning Points](https://github.com/haosheng00/SC1015-Mini-Project/edit/main/README.md#learning-points)
8. [References](https://github.com/haosheng00/SC1015-Mini-Project/edit/main/README.md#references)

## Motivation and Problem Statement
**Heart disease** is the leading cause of death, accounting for 32% of all deaths in the world. Given the severity of the situation, our group wants to reduce the implications of heart disease with early detection and intervention which allows for the best chance for successful treatment and survival.
- How can we assist doctors to speed up the diagnosis of heart disease to minimise further implications? 
- Which model is the best in predicting heart disease to aid in our goal of early detection?

## Models Used
- Decision Tree
- Random Forest
- Logistic Regression

## Data Preparation
After importing the dataset, we separated the numeric and categorical variables in different data frames for easier cleaning and renamed the 'sex' variable for easier visualisation in the portion of exploratory data analysis. The dataset is then checked for balance, after anomalies are then removed for higher precion and accuracy.

## Exploratory Data Analysis (EDA)
In the EDA, we gathered insights from the single and multi-variate analysis of the numeric variables, with the use of box plot, scatter plot, strip plot, histogram and correlation matrix. Whereas heatmaps are used for categorical variables. With these data-driven insights, we extracted the response variables to be used for our machine learning models.

## Machine Learning Models
To decide on the most suitable model for our dataset, we generated three models, namely decision tree, random forest and logistic regression. For random forest, we included an increment to the depth and estimators in a successful attempt to raise the classifiction accuracy of the model. Whereas for logistic regression, a comparison was made between the extracted dataframe and a cleaned full dataset with back elimination to evaluate the fit of the models. The extracted dataframe seems to be a better fit, with also higher accuracy. However, from the three models, Random Forest provides the highest accuracy and hence our ultimate model.

## Reflection

## Learning Points
- GitHub Collaboration
- Learnt new Machine Learning Models (Random Forest, Logistic Regression)
- Soft Skills such as Design Thinking to utilise models efficiently and effectively

## References
- https://ieee-dataport.org/open-access/heart-disease-dataset-comprehensive#files.
- https://www.who.int/news-room/fact-sheets/detail/cardiovascular-diseases-(cvds)#:~:text=Cardiovascular%20diseases%20(CVDs)%20are%20the,%2D%20and%20middle%2Dincome%20countries.
- https://www.myheart.org.sg/health/heart-disease-statistics/#:~:text=Singapore%20Statistics,to%20heart%20diseases%20or%20stroke.
- https://scholar.smu.edu/cgi/viewcontent.cgi?article=1041&context=datasciencereview.
- https://www.analyticsvidhya.com/blog/2021/06/understanding-random-forest/#:~:text=Random%20forest%20is%20a%20Supervised,average%20in%20case%20of%20regression.


## *Special Thanks to our Teaching Assistant Sun Chenyu for your guidance throughout the project and Course Instructors Associate Professor Bo An and Dr Sourav Sen Gupta for teaching the relevant content.*
