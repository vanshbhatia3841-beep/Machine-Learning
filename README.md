# 🤖 Machine Learning Lab Notebook

A comprehensive Jupyter Notebook covering fundamental Machine Learning and Data Analysis concepts, implemented in Python. This notebook progresses from basic NumPy operations to full ML model implementations.

---

## 📋 Table of Contents

1. [NumPy Array Operations](#1-numpy-array-operations)
2. [Pandas & Data Wrangling – Car Dataset](#2-pandas--data-wrangling--car-dataset)
3. [EDA & Visualization – Titanic Dataset](#3-eda--visualization--titanic-dataset)
4. [Linear Regression – CGPA vs Salary](#4-linear-regression--cgpa-vs-salary)
5. [K-Nearest Neighbors (KNN) – Pass/Fail Classifier](#5-k-nearest-neighbors-knn--passfail-classifier)
6. [Decision Tree Classifier – Tennis Dataset](#6-decision-tree-classifier--tennis-dataset)

---

## 📁 Files in This Repository

| File | Description |
|------|-------------|
| `ML.ipynb` | Main Jupyter Notebook with all experiments |
| `car_dataset.data` | Automobile dataset (26 features, 205 records) |
| `Tennis.csv` | Tennis play/no-play decision dataset |

---

## 🧪 Topics Covered

### 1. NumPy Array Operations
- Array creation, indexing, and modification
- Statistical operations: `size`, `dtype`, `median`, `min`, `max`, `sum`, `prod`, `cov`, `var`

### 2. Pandas & Data Wrangling – Car Dataset
- Loading a `.data` file with custom headers (26 columns including make, fuel-type, horsepower, price, etc.)
- Handling missing values represented as `?`
- Replacing NaN values with column mean
- Dropping rows with missing target values (`price`)
- Checking null counts per column after cleaning

### 3. EDA & Visualization – Titanic Dataset
- Exploratory Data Analysis using `pandas` and `seaborn`
- Visualizations: survival count plots, fare distribution by passenger class (`boxplot`)

### 4. Linear Regression – CGPA vs Salary
- Implemented using `sklearn.linear_model.LinearRegression`
- Trained on a simple CGPA–Salary dataset
- Outputs: slope (coefficient), intercept, and salary prediction for a given CGPA
- Scatter plot with regression line using `matplotlib`

### 5. K-Nearest Neighbors (KNN) – Pass/Fail Classifier
- Features: Hours Studied and Hours Slept
- Labels: Pass (1) / Fail (0)
- `n_neighbors=3`
- Decision boundary visualization using `matplotlib` mesh grid and `ListedColormap`

### 6. Decision Tree Classifier – Tennis Dataset
- Built using `sklearn.tree.DecisionTreeClassifier` with `criterion='entropy'`
- Label encoding of categorical features using `LabelEncoder`
- Full tree visualization with `plot_tree`

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
   git clone https://github.com/vanshbhatia3841-beep/ML-Lab.git
   cd ML-Lab
   ```

2. Install dependencies:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn
   ```

3. Launch the notebook:
   ```bash
   jupyter notebook ML.ipynb
   ```

> ⚠️ Make sure `car_dataset.data` and `Tennis.csv` are in the **same directory** as the notebook before running all cells.
> 
---

## 👤 Author

**Vansh**  
Manav Rachna University
