# 🏥 Disease Prediction Model

A machine learning project that predicts patient diseases based on symptom data and patient profiles using a Random Forest Classifier. 

## 📌 Project Overview
This project processes categorical medical data to predict whether a patient is positive or negative for specific diseases. By utilizing an ensemble learning method (Random Forest), the model accurately maps complex symptom patterns to correct diagnoses.

## 📊 Model Performance
* **Algorithm:** Random Forest (`n_estimators=100`)
* **Accuracy:** 85.7%
* **Evaluation Metrics Used:** Confusion Matrix and Classification Report (Precision, Recall, F1-Score) to ensure a comprehensive evaluation of the model's predictive power beyond simple accuracy.

## 🛠️ Technologies Used
* **Python 3**
* **Pandas:** Data manipulation and One-Hot Encoding (`pd.get_dummies`) to handle categorical text data.
* **Scikit-Learn:** Machine learning modeling, data splitting, and evaluation metrics.

## 📂 Dataset
The model is trained on the `Disease_symptom_and_patient_profile_dataset.csv`. 

**Note for running this code:** The script is currently configured to read the dataset directly from Google Drive:
```python
file_path = '/content/drive/MyDrive/Disease_symptom_and_patient_profile_dataset.csv'
