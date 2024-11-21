# Data Analysis of Olympic History Dataset
This project aims to analyze data using the "120 years of Olympic history: athletes and results" dataset from Kaggle. It is done in several steps:
<br>

1- Loading and Analyzing the Dataset <br>
2- Understanding the Data with Visualization <br>
3- Data Cleaning and Preprocessing <br>

## Problem Definition
Within the scope of this project, the physical characteristics and success status of Olympic athletes were analyzed. As a result of the analyses performed:

- It was observed that variables such as age, weight and height were effective on athlete performance.
- New features such as BMI were created and more information was obtained from the data set.
- It was predicted that this data could be used to predict the probability of athletes being successful and to optimize training programs.
- It is recommended to conduct modeling studies with classification or regression algorithms in the future.

## Key Findings of the Analysis
Analyzed how variables such as age, height, and weight affect winning Olympic medals.

- As a result of the correlation analysis, you found that certain variables have stronger relationships with winning medals (e.g., relationship between age and weight according to sport type).
- By creating new features such as BMI, it was shown that such metrics can play an important role in understanding the performance of athletes.

## Recommendations
Recommendations based on the findings:

- Data Usage: Based on the physical characteristics and past achievements of athletes, it can be predicted in which sport they will be more successful.

- Modeling and Prediction:This data can be used to predict medals with classification models or to predict performance scores with regression models. For example, a classification model can be established according to the sport branch (e.g., logistic regression, decision trees, or support vector machines).

- Practical Application: In line with the obtained predictions:
Coaches can prepare special programs for athletes.
Diet and training strategies can be developed to increase the performance of athletes.

## Proposed ML Algorithms
Suggest a model that is suitable for the type of data and the definition of the problem:

### For Classification Problems:
Support Vector Machines (SVM): It is an effective model especially for two-class or multi-class problems.
- Random Forest: An algorithm based on decision trees that can learn complex relationships between variables.
### For Regression Problems:
- Linear Regression: Simple but effective for understanding the effect of metrics such as height and weight on winning medals.
- Gradient Boosting (XGBoost, LightGBM): It is quite successful in learning complex data relationships.
### Reason for Selection:
If the outcome you want to predict is a class, such as whether an athlete will win a medal, classification algorithms can be used.
Regression models are more suitable for predicting a continuous value (e.g. performance score).

## Benefits for the Company
- Sports Performance Management Companies:
They can use their resources more efficiently by predicting the probability of athletes being successful. By optimizing their training processes, they can win more medals in the long run.

- Training and Development Programs:
Different strategies can be developed for athletes with lower potential. Targeted support can be provided for athletes with higher potential.

## Future Studies and Limitations
Incomplete or incorrect data in the data set can affect the analysis processes. It is important to improve data quality for better results.
Expanding the data set to different regions or sports branches can make it possible to create a more general model.
Hyperparameter optimization and model training with more data can be done to increase the accuracy of the proposed models.
