# 🤖 Machine Learning Lab Notebooks

A collection of four Jupyter Notebooks covering foundational Machine Learning concepts in Python — progressing from data preprocessing and encoding through regression and classification.

---

## 📋 Table of Contents

1. [Data Preprocessing & EDA – Titanic Dataset](#1-data-preprocessing--eda--titanic-dataset)
2. [Categorical Encoding – Salary Dataset](#2-categorical-encoding--salary-dataset)
3. [Linear Regression – CGPA vs Salary](#3-linear-regression--cgpa-vs-salary)
4. [Logistic Regression – Titanic Survival Classifier](#4-logistic-regression--titanic-survival-classifier)

---

## 📁 Files in This Repository

| File | Description |
|------|-------------|
| `Preprocessing.ipynb` | EDA and visualization on the Titanic dataset |
| `Encoding.ipynb` | One-Hot Encoding of categorical features |
| `Linear_Regression.ipynb` | Linear regression with sklearn and gradient descent from scratch |
| `Logistic_Regression.ipynb` | Full ML pipeline for binary classification |
| `titanic.csv` | Titanic passenger dataset (891 records, 12 features) |
| `Salary_Dataset.csv` | Salary dataset with country, experience, and purchase info |

---

## 🧪 Topics Covered

### 1. Data Preprocessing & EDA – Titanic Dataset
- Loading and inspecting a CSV dataset using `.head()` and `.info()`
- Visualizations using `matplotlib` and `seaborn`:
  - Count plot and pie chart for passenger gender distribution
  - Histogram and KDE distribution plot for Age
  - Box plot with annotated Q1, Median, and Q3 quartile lines

### 2. Categorical Encoding – Salary Dataset
- One-Hot Encoding a `country` column using `pd.get_dummies()`
- Concatenating encoded columns back into the original dataframe
- Reordering columns to produce a clean feature matrix

### 3. Linear Regression – CGPA vs Salary
- Fitting a `LinearRegression` model using `sklearn`
- Extracting and printing slope, intercept, and regression equation
- Predicting salary for a new CGPA value
- Plotting the data scatter and regression line with `matplotlib`
- Implementing gradient descent from scratch with configurable learning rate and iterations

### 4. Logistic Regression – Titanic Survival Classifier
- Feature selection (dropping `PassengerId`, `Name`, `Ticket`, `Cabin`)
- Handling missing values with `SimpleImputer` (mean for numerical, mode for categorical)
- One-Hot Encoding categorical features inside an sklearn `Pipeline`
- Parallel preprocessing with `ColumnTransformer`
- Model training with `LogisticRegression(solver='liblinear')`
- Evaluation with accuracy score, classification report (precision, recall, F1), and confusion matrix
- **Result:** ~79.3% accuracy on the test set

---

## 🛠️ Libraries Used

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn` (`sklearn`)

---

## ▶️ How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/vanshbhatia3841-beep/Machine-Learning
   cd Machine-Learning
   ```

2. Install dependencies:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn
   ```

3. Launch any notebook:
   ```bash
   jupyter notebook Preprocessing.ipynb
   ```
>
> 📝 If running locally, remove the `from google.colab import files` cell in `Preprocessing.ipynb` and load the CSV directly with `pd.read_csv("titanic.csv")`.

---

## 📈 Concepts Progression

```
Preprocessing  →  Encoding  →  Linear Regression  →  Logistic Regression
   (EDA)          (Features)      (Regression)          (Classification)
```

---

## 👤 Author

**Vansh**  
Manav Rachna University
