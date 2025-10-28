# 🌸 Iris Flower Classification — Machine Learning Project

## 📘 Objective
The objective of this project is to build and evaluate classification models that can accurately identify the species of an Iris flower (*Setosa*, *Versicolor*, or *Virginica*) based on its physical measurements such as sepal and petal dimensions.

---

## 🧩 Steps Performed

### 1. **Data Loading**
- Used the **Iris dataset** from the `sklearn.datasets` library.
- Loaded features and target values into pandas DataFrames for easy manipulation.

### 2. **Exploratory Data Analysis (EDA)**
- Displayed dataset shape, feature samples, and class distribution.
- Visualized relationships between features using **pair plots** and histograms to understand separability between species.

### 3. **Data Preprocessing**
- Split the dataset into **training and testing sets** using `train_test_split`.
- Scaled the features using **StandardScaler** for better model performance.
- Used **PCA (Principal Component Analysis)** to visualize feature variance reduction and dimensionality.

### 4. **Model Training**
- Implemented two classification algorithms:
  - **K-Nearest Neighbors (KNN)**
  - **Random Forest Classifier**
- Used a **Pipeline** for streamlined preprocessing and training.
- Performed **GridSearchCV** for hyperparameter tuning.

### 5. **Model Evaluation**
- Evaluated accuracy on test data.
- Displayed **confusion matrices**, **classification reports**, and **cross-validation scores**.
- Compared models to determine the most efficient classifier for this dataset.

---

## ⚙️ Tools & Libraries Used
| Category | Tools/Libraries |
|-----------|----------------|
| Data Handling | `pandas`, `numpy` |
| Visualization | `matplotlib`, `seaborn` |
| Machine Learning | `scikit-learn` (`Pipeline`, `RandomForestClassifier`, `KNeighborsClassifier``) |
| Evaluation | `accuracy_score`, `classification_report`, `confusion_matrix`, `cross_val_score` |

---

## 🏁 Outcome
- The **Random Forest Classifier** achieved the best performance among tested models, with high accuracy and strong generalization capability.
- Visualization of PCA components showed clear separation between Iris classes, confirming effective feature representation.
- The project demonstrates the complete machine learning workflow — from EDA and preprocessing to model tuning and evaluation.

---

