# titanic-survival-prediction-using-Pipeline
This repository contains a machine learning project built on the famous **Titanic dataset**.  
The goal is to predict whether a passenger survived or not using demographic and travel-related features.

The project is implemented **with and without scikit-learn pipelines** to clearly demonstrate both approaches.

---

## 📂 Project Structure

├── data  
│   └── titanic.csv  
├── notebooks  
│   ├── titanic_eda.ipynb  
│   ├── titanic_without_pipeline.ipynb  
│   └── titanic_with_pipeline.ipynb  
├── models  
│   └── trained_models.pkl  
├── README.md  

---

## 🔍 Dataset

- **Source:** Kaggle Titanic Dataset
- **Target Variable:** `Survived`
- **Features used:**
  - Sex
  - Age
  - Fare
  - Pclass
  - Embarked
  - Family-related features (if applicable)

---

## ⚙️ Techniques Used

- Exploratory Data Analysis (EDA)
- Handling missing values
- Feature encoding:
  - One-Hot Encoding
  - Ordinal Encoding
- Train-test split
- Machine Learning models:
  - Logistic Regression / Decision Tree (or your model)
- Model building:
  - Without Pipelines
  - With Pipelines (ColumnTransformer + Pipeline)

---

## 🚀 Why Pipelines?

- Cleaner and reusable code
- Prevents data leakage
- Easier model deployment
- Production-ready ML workflow

---

## 🛠 Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn

---

## 📊 Results

- Model performance evaluated using accuracy and classification metrics
- Pipeline-based approach provides cleaner and more maintainable implementation

---

## 📌 Learning Outcome

- Understood end-to-end ML workflow
- Difference between manual preprocessing and pipelines
- Practical usage of `ColumnTransformer` and `Pipeline`
- Common sklearn errors and how to debug them

---

## 👤 Author

**Aadil Nazir**  
Aspiring Data Analyst / Machine Learning Enthusiast

---

## ⭐ Future Improvements

- Hyperparameter tuning using GridSearchCV
- Try advanced models (Random Forest, XGBoost)
- Deploy the model using Flask or FastAPI
