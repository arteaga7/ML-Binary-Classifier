# ML-Binary-Classifier
This project analyzes the dataset of 10000 electric grids with 12 features.

**Objective:** To determine if the electric stability of the grid is stable (class 1) or inestable (class 0). This is, the binary classification problem is adressed in this document.

## Overview
First, the exploratory data analysis (EDA) is performed to show the data features in the non-cleaned dataset. Second, the data preprocessing is performed, which consist of:

a. Filling null values and dropping duplicates.

b. Processing outliers and multicollinearity.

c. Converting categorical variables into binary ones.

d. Scaling the data.

Third, the training and validation of the performance of 7 different ML algorithms are compared to solve the binary classification problem. The ML models are:

• Algorithm 1: **LogisticRegression**.

• Algorithm 2: **DecisionTreeClassifier**.

• Algorithm 3: **RandomForestClassifier**.

• Algorithm 4: **GradientBoostingClassifier**.

• Algorithm 4: **XGBClassifier (XGBoost library)**.

• Algorithm 4: **LGBMClassifier (LightGBM library)**.

• Algorithm 4: **CatBoostClassifier (CatBoost library)**.

Finally, the best algorithim is selected for this particular dataset to make predictions in production.

🛠️**Libraries used**: Pandas, Matplotlib, Seaborn, NumPy, SciPy, Scikit-learn, XGBoost, LightGBM, CatBoost.

- In folder "notebooks" is the Jupyter Notebook "binary_classifier.ipynb".

- In folder "data/raw" is the raw dataset.

- In folder "data/processed" is the processed data.

- In folder "models" are the scaler and the trained model.

## 🚀 Installation
1. Clone this repository:
```
git clone https://github.com/arteaga7/ML-Binary-Classifier.git
```
2. Set virtual environment and install dependencies:
```
python3 -m venv env && source env/bin/activate && pip3 install -r requirements.txt
```
3. Run Jupyter Notebook in notebooks/binary_classifier.ipynb.