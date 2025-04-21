# Patient-Diabetes-Prediction

**Project Overview:**

This project focuses on predicting whether a patient is diabetic using machine learning techniques. Health-related attributes such as glucose level, BMI, and age were analyzed to build an accurate and robust classification model. While no specific algorithm was prescribed, I independently chose and implemented XGBoost due to its strong performance during experimentation. The overall goal is to support early diagnosis and preventive healthcare strategies.

**Business Problem:**

Diabetes often remains undetected until complications occur. Healthcare providers need data-driven tools to identify high-risk individuals early and prioritize them for timely screening, lifestyle interventions, and further tests.

**Objectives:**

	•	Perform predictive analysis to determine whether a patient is diabetic.
	•	Explore, clean, and prepare the dataset for modeling.
	•	Handle class imbalance to ensure fair predictions.
	•	Experiment with classification algorithms and select the best-performing model (XGBoost was selected).
	•	Interpret key features influencing diabetes prediction.

**Dataset Description:**

	•	Features: Pregnancies, Glucose, Blood Pressure, Skin Thickness, Insulin, BMI, Diabetes Pedigree Function, Age
	•	Target: Outcome (1 = Diabetic, 0 = Non-diabetic)

**Tools & Libraries Used:**

	•	Python
	•	Pandas, NumPy – for data manipulation
	•	Matplotlib, Seaborn – for visualizations
	•	Scikit-learn – for preprocessing and evaluation
	•	imbalanced-learn (imblearn) – for SMOTE-based class balancing
	•	XGBoost – selected after testing multiple models
	•	GridSearchCV – for hyperparameter tuning

**Modeling Process:**

	1.	Preprocessing:
	•	Replaced or handled zero entries in key features like glucose and BMI.
	•	Scaled the data for optimal model performance.
	2.	Balancing the Dataset:
	•	Used SMOTE (from imblearn) to address class imbalance and ensure the model treated both diabetic and non-diabetic cases fairly.
	3.	Model Training:
	•	Tested various classifiers and selected XGBoost based on performance.
	•	Tuned hyperparameters using GridSearchCV.
	4.	Evaluation:
	•	Assessed using metrics like accuracy, precision, recall, F1-score, and ROC-AUC.
	•	Interpreted feature importance to understand key health indicators.

**Key Insights:**

	•	Glucose, BMI, and Age were the most influential features in predicting diabetes.
	•	Class imbalance significantly affected performance; balancing the dataset improved recall.
	•	XGBoost offered the best performance overall with strong generalization on unseen data.

**Future Improvements:**

	•	Build a Streamlit or Flask app for end-user interaction
	•	Integrate patient lifestyle or historical data for even better accuracy

**Contact:**

Oreselu Ireoluwatomiwa
[tomiwaoreselu@gmail.com]
