# predicton-of-cardiovascular-disease

There are 3 types of input features:

Objective: factual information; Examination: results of medical examination; Subjective: information given by the patient. Features:

Age | Objective Feature | age | int (days)
Height | Objective Feature | height | int (cm) |
Weight | Objective Feature | weight | float (kg) |
Gender | Objective Feature | gender | categorical code |
Systolic blood pressure | Examination Feature | ap_hi | int |
Diastolic blood pressure | Examination Feature | ap_lo | int |
Cholesterol | Examination Feature | cholesterol | 1: normal, 2: above normal, 3: well above normal |
Glucose | Examination Feature | gluc | 1: normal, 2: above normal, 3: well above normal |
Smoking | Subjective Feature | smoke | binary |
Alcohol intake | Subjective Feature | alco | binary |
Physical activity | Subjective Feature | active | binary |
Presence or absence of cardiovascular disease | Target Variable | cardio | binary |

##EDA
![image](https://github.com/vaisha01/predicton-of-cardiovascular-disease/assets/120439369/2f79309c-4b1b-4c7a-9de0-79db92a0bb31) ![image](https://github.com/vaisha01/predicton-of-cardiovascular-disease/assets/120439369/23401caf-f87d-4f2b-a420-d531c89a4d70)

From the above graphs,
1. Individuals between the ages of 55 and 65 have a higher risk of developing cardiovascular disease.
2. It is important to note that between the ages of 40 and 50, the likelihood of developing cardiovascular disease is lower. Additionally, the dataset shows that approximately 65% of cases are women and 35% are men, but the proportions of those with and without the disease are similar in both groups.


##
   
![image](https://github.com/vaisha01/predicton-of-cardiovascular-disease/assets/120439369/bf2fe4b0-166c-443d-a1f5-83f11a0b4278)
It's important to keep in mind that even if you have normal glucose and cholesterol levels, you may still be at a higher risk for cardiovascular disease. Additionally, avoiding smoking and alcohol may not completely shield you from the risk of developing diseases. It's crucial to maintain a healthy lifestyle and stay on top of regular check-ups with your healthcare provider to monitor your overall health and well-being.


##
The correlation plot of independent features is shown below.
The BMI, calculated using weight and height, strongly correlates with weight. The systolic and diastolic blood pressure measurements are highly correlated at 73%.
 ![image](https://github.com/vaisha01/predicton-of-cardiovascular-disease/assets/120439369/238d93f6-3af4-4c1f-8358-7227bdc0bb1a)


##
##Result
Based on our analysis, the Random Forest model provides more accurate results in comparison to Decision Tree, Logistic Regression, and KNN. Random Forest has high accuracy, precision, recall, and F1 score, making it the best machine learning model for predicting cardiovascular disease.

![image](https://github.com/vaisha01/predicton-of-cardiovascular-disease/assets/120439369/93abccb6-f359-469a-a2df-b0482ec06cf0)
