# Stroke-Prediction

Introduction 

A stroke is a life-threatening condition that occurs when the blood vessel carrying nutrients to the brain is blocked or ruptured. According to the WHO, strokes are the second leading cause of death. In addition, there is a 50% chance that the survivors of a stroke become disabled.
However, according to the CDC, 80% of strokes are preventable. The purpose of this project is to identify whether an individual is likely to get a stroke based on factors such as age, gender, pre-existing conditions, lifestyle, habits, family history, etc. Our analysis can assist the medical field in determining which factors and health conditions can more likely increase your chance of getting a stroke. This way, medical professionals can advise patients with strategies to target specific factors to decrease one’s chance of a stroke. 

The project is subdivided into the following sections: 
1.	Obtaining and review the raw data 
2.	Data processing 
3.	Determining the correlation between variables
4.	Approach
5.	Exploratory data analysis
6.	Supervised learning
7.	Conclusion 

Data
The data used is “Stroke Prediction Dataset” by Fedesoriano from Kaggle. The source of the data has been made confidential by the sharing party. 
Dataset URL - https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset?select=healthcare-dataset-stroke-data.csv 
It contains the following columns:
1) ID: This is a unique identifier for the individual
2) gender: "Male", "Female" or "Other"
3) age: Age of the individual
4) hypertension: 0 if the individual does not have hypertension, 1 if the individual has hypertension
5) heart_disease: 0 if the individual does not have any heart diseases, 1 if the individual has a heart disease
6) ever_married: "No" or "Yes"
7) work_type: The type of work the individual is involved in. It is  "children" for kids who are not working, "Govt_jov" for individuals in government jobs, "Never_worked" for individuals who have never worked, "Private" for employees in the private sector, or "Self-employed".
8) Residence_type: "Rural" or "Urban"
9) avg_glucose_level: Average glucose level in blood
10) bmi: Body mass index
11) smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown" (if this information for individuals is not available)
12) stroke: 1 if the patient had a stroke or 0 if not
