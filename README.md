# 🏠 RealEstateAI Solutions

A Machine Learning project for **real estate price prediction** using **regularized regression models**: Ridge, Lasso, and Elastic Net.

---

## 📌 Goal

Build a predictive system to estimate housing prices and improve **generalization performance** through **regularization techniques**.  
Ideal for real estate agents and investors who want to make data-driven decisions.

---

## 🛠️ Technologies & Libraries

- Python 3.x  
- `pandas`, `numpy`, `scikit-learn`  
- `matplotlib`, `seaborn`

---

## 📁 Dataset

The dataset used is available at: https://proai-datasets.s3.eu-west-3.amazonaws.com/housing.csv

It contains 13 predictive features, including:
- Area (sqft)
- Number of bedrooms and bathrooms
- Availability of services (AC, garage, heating, etc.)
- Furnishing status

---

## ⚙️ Workflow

### 1. 📊 Data Preparation
- Load the dataset
- Categorical features already encoded
- Train-test split
- **Standardization** of numeric features

### 2. 🤖 Model Training
- **Ridge Regression**
- **Lasso Regression**
- **Elastic Net Regression**
- Training on the train set
- 5-fold cross-validation

### 3. 📈 Performance Evaluation
For each model, the following metrics are calculated:
- **MSE** (Mean Squared Error) on train and test set
- **R² Score** on train and test set
- **Number of non-zero coefficients** → indicates model sparsity

### 4. 📊 Visualization
- Line or bar plots to compare MSE and R² scores across models
- **Residual plots** to assess model fit

---

---

## 🧠 Future Improvements

- Support for `log(price)` transformation  
- Web interface using **Streamlit** or **Flask**  
- Automatic feature selection  
- Testing on additional real estate datasets  

---

## 👨‍💻 Author

**Developed by:** Riccardo Ciullini
📧 Contact: https://www.linkedin.com/in/riccardo-ciullini-692792285/
