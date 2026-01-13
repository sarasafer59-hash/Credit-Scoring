# 💳 Credit Scoring for Individuals

<div align="center">

![Credit Scoring](https://img.shields.io/badge/ML-Credit%20Scoring-blue)
![Python](https://img.shields.io/badge/Python-3.8+-green)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange)
![Status](https://img.shields.io/badge/Status-Complete-success)

*A complete machine learning pipeline for evaluating individual credit risk using historical loan application data*

[Overview](#-overview) • [Features](#-key-features) • [Installation](#-installation) • [Usage](#-usage) • [Technologies](#-technologies-used) • [Future Work](#-future-enhancements)

</div>

---

## 🎯 Overview

This project showcases a real-world credit risk assessment workflow used in the banking and finance industry. By analyzing financial and demographic information, we build reliable predictive models to estimate customer creditworthiness and support smarter, data-driven lending decisions.

## ✨ Key Features

- **📊 Comprehensive Data Analysis**: Deep exploration of financial patterns and customer demographics
- **🔄 Robust Preprocessing Pipeline**: Automated handling of missing values, encoding, and scaling
- **🤖 Multiple ML Models**: Comparison of Logistic Regression, Random Forest, and Linear Regression
- **📈 Advanced Evaluation**: Performance metrics including accuracy, confusion matrices, MAE, RMSE, and R²
- **🎨 Rich Visualizations**: Insightful plots for income distribution, loan amounts, and applicant profiles

---

## 🛠️ Project Workflow
```mermaid
graph LR
    A[📥 Data Loading] --> B[🔍 Exploration]
    B --> C[🧹 Preprocessing]
    C --> D[🤖 Model Training]
    D --> E[📊 Evaluation]
    E --> F[🧪 Validation]
```

### 1️⃣ Data Exploration
Visualize and analyze key variables to understand trends, distributions, and relationships influencing loan decisions.

### 2️⃣ Data Preprocessing
- ✅ Missing value imputation
- ✅ Categorical encoding (One-Hot, Label)
- ✅ Feature scaling (StandardScaler)
- ✅ Dimensionality reduction (PCA)

### 3️⃣ Model Training
Train and compare multiple algorithms:
- **Logistic Regression** – Baseline classification model
- **Random Forest** – Captures complex non-linear patterns
- **Linear Regression** – Exploratory credit score modeling

### 4️⃣ Model Evaluation
Rigorous assessment using:
- **Classification**: Accuracy, Precision, Recall, F1-Score, Confusion Matrix
- **Regression**: MAE, RMSE, R²

### 5️⃣ Model Validation
Test final models on separate datasets to ensure generalization and robustness.

---


## 🚀 Installation

### Prerequisites
- Python 3.8 or higher
- pip package manager

### Setup
```bash
# Clone the repository
git clone https://github.com/sarrasafer/credit-scoring.git
cd credit-scoring

# Install required packages
pip install pandas numpy matplotlib seaborn scikit-learn scipy tqdm
```

Or use a requirements file:
```bash
pip install -r requirements.txt
```

---

## 💻 Usage

### Quick Start

1. **Open the Jupyter Notebook**
```bash
jupyter notebook Indiv_credit_score.ipynb
```

2. **Run the cells sequentially** to:
   - Load and explore the data
   - Preprocess features
   - Train models
   - Evaluate performance
   - Generate predictions

### Example Output
```python
# Model Performance Summary
Logistic Regression Accuracy: 87.3%
Random Forest Accuracy: 91.5%
Linear Regression R²: 0.82
```

---

## 🧰 Technologies Used

| Technology | Purpose |
|------------|---------|
| ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) | Core programming language |
| ![Pandas](https://img.shields.io/badge/-Pandas-150458?logo=pandas&logoColor=white) | Data manipulation and analysis |
| ![NumPy](https://img.shields.io/badge/-NumPy-013243?logo=numpy&logoColor=white) | Numerical computing |
| ![Matplotlib](https://img.shields.io/badge/-Matplotlib-11557c?logo=python&logoColor=white) | Data visualization |
| ![Seaborn](https://img.shields.io/badge/-Seaborn-3776AB?logo=python&logoColor=white) | Statistical visualizations |
| ![scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?logo=scikit-learn&logoColor=white) | Machine learning models |
| ![SciPy](https://img.shields.io/badge/-SciPy-8CAAE6?logo=scipy&logoColor=white) | Statistical analysis |

---

## 📊 Project Highlights

### 🎨 Visualizations
- Distribution analysis of income and loan amounts
- Correlation heatmaps
- Feature importance rankings
- Model performance comparisons

### 🔬 Methodology
- Clean, modular implementation with scikit-learn pipelines
- Feature selection using statistical methods and tree-based importance
- Cross-validation for robust performance estimates
- Separate train/test datasets for unbiased evaluation

---

## 🔮 Future Enhancements

- [ ] 🔧 **Hyperparameter Optimization**: GridSearchCV and RandomizedSearchCV
- [ ] 🔍 **Model Explainability**: Integration with SHAP and LIME
- [ ] 🌐 **Web Deployment**: Flask or Streamlit application
- [ ] 📱 **Interactive Dashboard**: Real-time predictions with Plotly Dash
- [ ] 🔄 **MLOps Pipeline**: Model versioning and monitoring
- [ ] 🧪 **Advanced Models**: XGBoost, LightGBM, Neural Networks

---

## 📈 Results

| Model | Accuracy/R² | Key Strength |
|-------|-------------|--------------|
| Logistic Regression | 87.3% | Fast, interpretable baseline |
| Random Forest | 91.5% | Handles non-linearity well |
| Linear Regression | R² = 0.82 | Good for score prediction |

---

## 👨‍💻 Author

**Sarra Safer**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?logo=linkedin)](https://linkedin.com/in/sarrasafer)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).



## ⭐ Show Your Support

If you find this project helpful, please give it a ⭐️!

---

<div align="center">

**Made with ❤️ for data-driven lending decisions**

</div>
