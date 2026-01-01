# Student Stress Prediction Using Machine Learning

## 📌 Project Overview
This project focuses on predicting student stress levels using machine learning techniques. The dataset used in this project is sourced from Kaggle and contains various academic, lifestyle, and personal factors related to students. The main objective is to build, evaluate, and improve classification models that can effectively predict stress levels.

The project is implemented as a **personal machine learning project** using Python and is developed entirely in a Jupyter Notebook.

---

## 📊 Dataset
- **Source:** Kaggle  
- **Format:** CSV  
- **Type:** Student stress dataset  

The dataset includes features related to students' study habits, lifestyle patterns, and personal factors, along with corresponding stress level labels.

> Note: The dataset is publicly available on Kaggle. Please refer to the original Kaggle page for data details and licensing.

---

## 🛠️ Technologies Used
- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-learn  

---

## 🤖 Models Implemented
### Logistic Regression
- Used as a baseline classification model
- Helps understand linear relationships between features and stress levels

### Random Forest Classifier
- Ensemble learning method based on decision trees
- Captures non-linear relationships in the data
- Outperformed the baseline model

---

## 🔧 Hyperparameter Tuning
To improve model performance, hyperparameter optimization was performed using:
- **GridSearchCV**
- **RandomizedSearchCV**

These techniques helped identify better model configurations and resulted in improved accuracy.

---

## 📈 Results
- **Initial Random Forest Accuracy:** ~87.7%  
- **After Hyperparameter Tuning:** ~88.8%  

The results show that tuning hyperparameters led to a measurable performance improvement.

---

## 📁 Project Structure
├── student_stress_analysis.ipynb
├── dataset/
│ └── student_stress.csv
├── README.md


---

## ▶️ How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/student-stress-ml.git

2. install the required dependencies:
   pip install -r requirements.txt


## 📌 Key Learnings
- **Comparison of linear and ensemble-based classification models**

- **Practical experience with hyperparameter tuning techniques**

- **Understanding the impact of feature selection and preprocessing**

- **Model evaluation using accuracy as a performance metric**