# Diabetes_Prediction_SVC
🩺 Diabetes Prediction using Support Vector Classifier (SVC)

A machine learning project to predict whether a person is diabetic or not using the Support Vector Classifier (SVC) model. This project uses the Pima Indians Diabetes Dataset and is implemented using Python and popular ML libraries like pandas, NumPy, Matplotlib, Seaborn, and scikit-learn.

📊 Dataset
Source: Pima Indians Diabetes Dataset

Features: Pregnancies, Glucose, Blood Pressure, Skin Thickness, Insulin, BMI, Diabetes Pedigree Function, Age

Target: Outcome (0 = Non-diabetic, 1 = Diabetic)

Data Preprocessing:
Features include: Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, and Age.

Applied train-test split (75% train, 25% test)

Used StandardScaler to normalize the data.

 EDA Highlights:
Pairplot visualized variable distributions and relationships.

Correlation Matrix:

Most correlated feature with diabetes (Outcome) is Glucose (0.47).

Other positively correlated features: BMI (0.29), Age (0.24), Pregnancies (0.22)



#Clone the repository:
git clone https://github.com/Ajay-Kumar-Prasad/Diabetes_Prediction_SVC.git
cd Diabetes_Prediction_SVC

pip install -r requirements.txt