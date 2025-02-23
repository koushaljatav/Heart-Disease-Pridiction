Heart Disease Prediction Project
Overview
This project aims to predict the likelihood of heart disease in patients using machine learning techniques. The dataset used contains various medical and demographic features, and the goal is to build a model that can accurately classify whether a patient has heart disease or not.

Dataset
The dataset used in this project is the Heart Disease UCI Dataset, which contains the following features:

Age: Age of the patient

Sex: Gender of the patient (1 = male, 0 = female)

Chest Pain Type: Type of chest pain (4 values)

Resting Blood Pressure: Resting blood pressure (in mm Hg)

Cholesterol: Serum cholesterol level (in mg/dl)

Fasting Blood Sugar: Fasting blood sugar > 120 mg/dl (1 = true, 0 = false)

Resting ECG: Resting electrocardiographic results (3 values)

Max Heart Rate: Maximum heart rate achieved

Exercise Induced Angina: Exercise-induced angina (1 = yes, 0 = no)

ST Depression: ST depression induced by exercise relative to rest

Slope: Slope of the peak exercise ST segment

Number of Major Vessels: Number of major vessels colored by fluoroscopy

Thalassemia: Thalassemia type (3 values)

Target: Presence of heart disease (1 = yes, 0 = no)

Tools and Technologies
Python: Primary programming language

Pandas: Data manipulation and analysis

NumPy: Numerical computations

Scikit-learn: Machine learning algorithms and tools

Matplotlib/Seaborn: Data visualization

Imbalanced-learn: Handling class imbalance (if applicable)

Jupyter Notebook: Interactive development environment

Steps
Data Preprocessing:

Handle missing values (if any).

Encode categorical variables.

Normalize/scale numerical features.

Split the dataset into training and testing sets.

Exploratory Data Analysis (EDA):

Visualize the distribution of features.

Analyze correlations between features and the target variable.

Identify and handle class imbalance (if applicable).

Feature Selection:

Use techniques like correlation analysis, feature importance, or recursive feature elimination to select the most relevant features.

Model Building:

Train and evaluate multiple machine learning models, such as:

Logistic Regression

Decision Trees

Random Forest

Support Vector Machines (SVM)

Gradient Boosting (e.g., XGBoost, LightGBM)

Use cross-validation to ensure model robustness.

Model Evaluation:

Evaluate models using metrics like accuracy, precision, recall, F1-score, and ROC-AUC.

Compare performance across different models.

Handling Class Imbalance:

Apply techniques like SMOTE (Synthetic Minority Over-sampling Technique) or ADASYN to handle imbalanced datasets.

Hyperparameter Tuning:

Use GridSearchCV or RandomizedSearchCV to optimize model hyperparameters.

Final Model Deployment:

Save the best-performing model using joblib or pickle.

Deploy the model using a web framework like Flask or FastAPI (optional).

Results
Achieved an accuracy of 100% using the logictic regression model.

