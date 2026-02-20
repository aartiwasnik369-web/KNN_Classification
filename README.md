# Task 6: K-Nearest Neighbors (KNN) Classification

## Objective
To understand and implement the K-Nearest Neighbors (KNN) algorithm for classification problems using Scikit-learn.

---

## Dataset Used
Iris Dataset  

The dataset contains 150 samples of iris flowers belonging to 3 species:
- Setosa
- Versicolor
- Virginica

Features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

---

## Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Steps Performed

### Data Loading
Loaded the Iris.csv dataset using pandas.

### Data Preprocessing
- Removed unnecessary columns (Id column)
- Separated features (X) and target (y)

### Train-Test Split
Split the dataset into:
- 80% Training data
- 20% Testing data

### Feature Scaling (Normalization)
Used StandardScaler to normalize features because KNN is distance-based.

### Model Training
Used:
```python
KNeighborsClassifier(n_neighbors=3)
