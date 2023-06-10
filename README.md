# Stroke Prediction Using Electronic Health Records (EHRs)

![download](https://github.com/OmarAlkousa/Stroke-Prediction-Using-Electronic-Health-Records/assets/64659365/d29c2033-6390-426b-aa74-b2f3cf98fb41)

## How National Health System ([NHS](https://www.nhs.uk/conditions/stroke/#:~:text=A%20stroke%20is%20a%20serious,damage%20is%20likely%20to%20happen.)) define STROKE
"A stroke is a serious life-threatening medical condition that happens when the blood supply to part of the brain is cut off."
"Strokes are a medical emergency and urgent treatment is essential."
"The sooner a person receives treatment for a stroke, the less damage is likely to happen."
## Stroke in the perspective of the World Health Organization ([WHO](http://www.emro.who.int/health-topics/stroke-cerebrovascular-accident/index.html)):
"Annually, 15 million people worldwide suffer a stroke. Of these, 5 million die and another 5 million are left permanently disabled, placing a burden on family and community. Stroke is uncommon in people under 40 years; when it does occur, the main cause is high blood pressure. However, stroke also occurs in about 8% of children with sickle cell disease."

## About the Dataset
A brief summary of the [dataset](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset):

This dataset is used to predict whether a patient is likely to get stroke based on the input parameters like gender, age, various diseases, and smoking status. Each row in the data provides relavant information about the patient. The dataset has one target (stroke), and 11 columns as described below:



1.   id: unique identifier
2.   gender: "Male", "Female" or "Other"
3.   age: age of the patient
4.   hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
5.   heart_disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
6.   ever_married: "No" or "Yes"
7.   work_type: "children", "Govt_job", "Never_worked", "Private" or "Self-employed"
8.   Residence_type: "Rural" or "Urban"
9.   avg_glucose_level: average glucose level in blood
10.  bmi: body mass index
11.  smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown"*
12.  stroke: 1 if the patient had a stroke or 0 if not

**Note**: "Unknown" in smoking_status means that the information is unavailable for this patient.

![Untitled](https://github.com/OmarAlkousa/Stroke-Prediction-Using-Electronic-Health-Records/assets/64659365/991e9e17-1273-4e95-8737-4ce51221b99a)

