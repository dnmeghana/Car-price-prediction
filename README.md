# Car Price Prediction Using Linear and Lasso Regression

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Environment](https://img.shields.io/badge/Environment-Google_Colab-orange)](https://colab.research.google.com/)
[![Framework](https://img.shields.io/badge/Machine_Learning-Scikit--Learn-green)](https://scikit-learn.org/)

The focus of this project is to develop a machine learning model using Python that can accurately predict the price of a used car based on various dataset features. By leveraging regression techniques, this tool helps buyers and sellers make data-driven, informed purchases.

---

## 📌 Project Overview

Predicting the resale value of a car involves analyzing multiple factors such as fuel type, seller type, and transmission. This project explores, cleans, and processes a car dataset, applying **Linear Regression** and **Lasso Regression** models to evaluate and compare their predictive accuracy using $R^2$ evaluation metrics.

### Key Features
* **Data Preprocessing:** Handling missing values and encoding categorical text features into numerical integers.
* **Exploratory Data Analysis (EDA):** Inspecting dataset shapes, distributions, and structural characteristics.
* **Comparative Modeling:** Implementing and comparing ordinary least squares (Linear Regression) against L1-regularized regression (Lasso).
* **Performance Evaluation:** Utilizing $R^2$ (Coefficient of Determination) metrics and scatter plots for error visualization.

---

## 📂 Repository Structure

```text
├── Car Price Prediction Literature Survey.pdf  # Background research & literature review
├── Car Price Prediction_PPT.pptx              # Project presentation slides
├── Car Price Prediction_PROJECT_REPORT.pdf    # Comprehensive technical project report
├── Car Price Prediction_PROJECT.zip           # Compressed source code & notebook assets
├── car.csv                                    # Used car dataset (to be uploaded)
└── README.md                                  # Project documentation
```
## 🚀 Getting Started
Follow these steps to set up and run the project using Google Colab.

### Prerequisites
Make sure you have the following Python libraries installed if you choose to run locally (Google Colab comes with these pre-installed):
```bash
pip install pandas numpy seaborn matplotlib scikit-learn
```

### Execution via Google Colab
1. Navigate to [Google Colab](https://colab.research.google.com/).
2. Extract the notebook file from Car Price Prediction_PROJECT.zip and upload it to Colab.
3. Upload the dataset file named car.csv into your Google Colab session storage.
4. Run each cell sequentially from the beginning to execute the workflow.

## 🛠️ Step-by-Step Implementation Workflow
**1.Library Importation:** Load essential data science and ML packages (`pandas`, `seaborn`, `matplotlib`, `sklearn`).

**82. Data Ingestion:** Load data from `car.csv` into a Pandas DataFrame.

**3. Data Inspection:** Examine dataset shape, check for null entries using `.isnull()`, and count unique categorical variables (`fuel`, `seller_type`, `transmission`).

**4. Categorical Encoding:** Map text-based categorical columns to numerical integers using the `.replace()` function.

**5. Feature Allocation:** Separate independent feature variables ($X$) from the target price variable ($Y$).

**6. Data Splitting:** Partition data into training (90%) and testing (10%) sets using:
```python
X_train, X_test, Y_train, Y_test = train_test_split(X, Y, test_size=0.1, random_state=2)
```
**7. Model Training (Linear Regression):** Fit the Linear Regression model on the training data.

**8. Evaluation (Linear Regression):** Predict, calculate the $R^2$ score, and plot scatter graphs for both the training and test data slices.

**9. Model Training & Evaluation (Lasso Regression):** Repeat the training and evaluation steps (steps 7–8) using the Lasso Regression model for comparison.
---

## 📊 Evaluation Results

Once you run your code, you can fill in your exact performance outputs here:

| Model              | Training $R^2$ Score | Test $R^2$ Score |
|-------------------|---------------------|------------------|
| **Linear Regression** | _[Insert Score]_     | _[Insert Score]_  |
| **Lasso Regression**  | _[Insert Score]_     | _[Insert Score]_  |

---

### 👤 Contributor

- **Meghana N** - [@dnmeghana](https://github.com/dnmeghana)
