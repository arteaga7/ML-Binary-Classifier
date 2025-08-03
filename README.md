# ML-Binary-Classifier
This project analyzes the dataset of 10000 electric grids with 12 features.

**Objective:** To determine if the electric stability of the grid is stable (class 1) or inestable (class 0). This is, the binary classification problem is adressed in this document.

## Overview
First, the exploratory data analysis (EDA) is performed to show the data features in the non-cleaned dataset. Second, the data preprocessing is performed, which consist of:

a. Filling null values and dropping duplicates.

b. Processing outliers and multicollinearity.

c. Converting categorical variables into binary ones.

d. Scaling the data.

Third, the training and validation of the performance of 4 different ML algorithms are compared to solve the binary classification problem. The ML models are:

• Algorithm 1: **Logistic Regression**.

• Algorithm 2: **Decision Tree Classifier**.

• Algorithm 3: **Random Forest Classifier**.

• Algorithm 4: **Gradient Boosting Classifier**.

Finally, the best algorithim is selected for this particular dataset.

🛠️**Libraries used**: Pandas, Matplotlib, Seaborn, NumPy, SciPy, Scikit-learn.

The Jupyter Notebook is in scripts/binary_classifier.ipynb.

## 🚀 Installation
1. Clone this repository:
```
git clone https://github.com/arteaga7/ML-Binary-Classifier.git
```
2. Set virtual environment and install dependencies:
```
python3 -m venv env
source env/bin/activate
pip3 install -r requirements.txt
```
3. Run Jupyter Notebook in scripts/binary_classifier.ipynb.