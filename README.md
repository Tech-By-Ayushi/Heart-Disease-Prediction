# ❤️ Heart Disease Prediction

A machine learning project that predicts the likelihood of heart disease using medical data. The model uses **Logistic Regression** and **Random Forest** classifiers to make predictions based on patient health indicators.

## 🛠️ Technologies Used

- **Python**
- **Pandas** – Data manipulation and cleaning
- **NumPy** – Numerical operations
- **scikit-learn** – Machine learning modeling
- **Matplotlib** – Data visualization

## 📊 Features

- Built predictive models using Logistic Regression and Random Forest algorithms.
- Preprocessed data to handle missing values and normalize numerical features.
- Created insightful visualizations to explore correlations and trends for feature selection.
- Evaluated models using accuracy, precision, recall, and confusion matrix.


### 🩺 Dataset Features

The dataset includes the following medical attributes used to predict heart disease:

- `age` – Age of the patient
- `sex` – Gender (1 = male, 0 = female)
- `cp` – Chest pain type (0 to 3)
- `trestbps` – Resting blood pressure (in mm Hg)
- `chol` – Serum cholesterol in mg/dl
- `fbs` – Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
- `restecg` – Resting electrocardiographic results (0 to 2)
- `thalach` – Maximum heart rate achieved
- `exang` – Exercise-induced angina (1 = yes; 0 = no)
- `oldpeak` – ST depression induced by exercise relative to rest
- `slope` – Slope of the peak exercise ST segment
- `ca` – Number of major vessels (0–3) colored by fluoroscopy
- `thal` – Thalassemia (1 = normal; 2 = fixed defect; 3 = reversible defect)
- `target` – Diagnosis of heart disease (1 = presence; 0 = absence)

> These features are used as inputs for training the machine learning model to predict the likelihood of heart disease.


## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/heart-disease-prediction.git
   cd heart-disease-prediction

2. 📦 Install project dependencies
pip install -r requirements.txt

3. ▶️ Run the heart disease prediction script
python heart_disease_prediction.py

# 📌 Results:
 - Both Logistic Regression and Random Forest performed well.
 - Random Forest had higher accuracy due to its ensemble learning ability.
 - Evaluated using metrics: accuracy, precision, recall, F1-score, confusion matrix.

# ✅ Future Improvements:
 - Add a web interface using Flask or Streamlit.
 - Expand the dataset for better generalization.
 - Perform hyperparameter tuning (e.g., GridSearchCV).

