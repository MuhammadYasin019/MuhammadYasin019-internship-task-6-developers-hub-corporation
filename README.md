# Churn Prediction (Machine Learning Pipeline)

## 🎯 Objective
The purpose of this project is to predict **customer churn** using classical machine learning models.  
The pipeline includes preprocessing, training, evaluation, and saving the model as a `.pkl` file for reuse.

---

## ⚙️ Methodology / Approach
1. **Data Preprocessing**
   - Handled missing values
   - Encoded categorical features
   - Scaled numerical features

2. **Model Training**
   - Tested models: Logistic Regression, Random Forest, etc.
   - Tuned hyperparameters using GridSearchCV
   - Selected the best-performing model

3. **Pipeline Export**
   - Entire preprocessing + model pipeline exported as `churn_pipeline.pkl`
   - Can be reloaded with `joblib` for predictions on new data

---

## 📊 Key Results / Observations
- Best model: **[your best model here, e.g., Logistic Regression]**
- Accuracy: **X%**  
- Precision/Recall: **Y/Z**  
- Model performed well on unseen test data  

---

## 🚀 How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/churn-prediction.git
   cd churn-prediction
