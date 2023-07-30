# Stroke_Prediction
Stroke Prediction Project
# Jinglin's Insights from the stroke prediction project are as follows:

Gender Analysis: Although females appear more frequently in our dataset, they also surpass males in the stroke sample space. Additionally, males show higher vulnerability to strokes in their early 50s and 60s, while the median age for stroke in females is around 75-79.

Marriage and Residence: Marriage status and residence type distributions do not seem to significantly influence stroke-positive individuals. Residence type appears to have a nearly uniform distribution, while one value dominates the marriage status.

Numeric Correlation: There is no clear numeric correlation between the stroke attribute and other numeric attributes in our dataset.

Addressing Imbalance: To address the imbalanced dataset, we created an upsampled version where both sample outcomes are uniformly distributed. This step aims to improve the models' ability to identify key characteristics of stroke-prone individuals.

Model Performance: During cross-validation testing, random forest and decision tree models displayed the best performance, with less overfitting on the sample data. To validate their predictive abilities on stroke-prone individuals, we tested these models again on the original data before upsampling.
# Introduction
Stroke is a leading cause of death and disability worldwide, primarily attributed to atherothromboembolism and cardiogenic embolism. It poses a significant health challenge, with certain risk factors such as high blood pressure, cholesterol, smoking, and diabetes contributing to atherothromboembolic ischemic strokes, while atrial fibrillation and ischemic heart disease are linked to cardiogenic ischemic strokes (Hankey, G. J., 2005).

To combat the burden of stroke, prevention strategies focus on two approaches: a 'population' approach involving public education and legislation to target community risk factors, and a 'high-risk' approach aimed at identifying at-risk individuals and providing optimal medical therapies, including controlling risk factors and administering antithrombotic treatments.

Approximately 75% of strokes are first-time occurrences, emphasizing the importance of preventing initial strokes. Controlling vascular risk factors, such as blood pressure and cholesterol levels, plays a crucial role in preventing atherothromboembolic ischemic strokes. Lifestyle changes like quitting smoking, managing blood glucose, and adopting a healthy diet and exercise routine can further reduce the risk of stroke (Hankey, G. J., 2005).

# Dataset Information
According to the World Health Organization (WHO), stroke is the 2nd leading cause of death globally, accounting for around 11% of total deaths. This dataset is utilized to predict whether a patient is likely to experience a stroke based on various input parameters, including gender, age, presence of hypertension, heart disease, marriage status, work type, residence type, average glucose level, body mass index (BMI), and smoking status.

# Attribute Information:

id: Unique identifier
gender: "Male", "Female," or "Other"
age: Age of the patient
hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
heart_disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has heart disease
ever_married: "No" or "Yes"
work_type: "Children", "Govt_jov", "Never_worked", "Private," or "Self-employed"
Residence_type: "Rural" or "Urban"
avg_glucose_level: Average glucose level in blood
bmi: Body mass index
smoking_status: "Formerly smoked," "Never smoked," "Smokes," or "Unknown"* (Note: "Unknown" indicates unavailable information)
stroke: 1 if the patient had a stroke or 0 if not
References
Hankey, G. J. (2005). Preventable stroke and stroke prevention. Journal of Thrombosis and Haemostasis, 3(8), 1638-1645.
Kaggle Dataset Source
Reference Notebooks: Notebook 1, Notebook 2

The dataset used for this stroke prediction project can be accessed from Kaggle: Stroke Prediction Dataset.

Please refer to the provided Kaggle notebooks for additional insights and predictive analyses related to stroke prediction.
