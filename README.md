# Heart-Disease-Prediction-

The dataset contains 76 attributes, including the predicted attribute, but all published experiments refer to using a subset of 14 of them. The "target" field refers to the presence of heart disease in the patient. It is integer valued 0 = no disease and 1 = disease.
The features are as follows:

age

sex

chest pain type (4 values)

resting blood pressure

serum cholestoral in mg/dl

fasting blood sugar > 120 mg/dl

resting electrocardiographic results (values 0,1,2)

maximum heart rate achieved

exercise induced angina

oldpeak = ST depression induced by exercise relative to rest

the slope of the peak exercise ST segment

number of major vessels (0-3) colored by flourosopy

thal: 0 = normal; 1 = fixed defect; 2 = reversable defect

Three models are trained after manipulating the data using data visualization.
Logistic Regression,
K-Nearest Neighbour Classifier,
Random Forest Classifier.

Evaluation metrics for the project are :
ROC curve

Confusion_matrix

Precison

Recall

F1_score

Classification_report.

HyperParamater Tuning using RandomizedSearchCV and GridCV.

