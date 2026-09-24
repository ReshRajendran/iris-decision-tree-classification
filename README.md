# Iris Flower Classification using Decision Tree

A machine learning project that classifies Iris flower species using a Decision Tree classifier, with a visualized decision tree.

## 📌 Overview
This project uses the classic **Iris dataset** to predict the species of an iris flower (*Setosa*, *Versicolor*, or *Virginica*) based on four features: sepal length, sepal width, petal length, and petal width.

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn (DecisionTreeClassifier, train_test_split)
- Matplotlib (tree visualization)

## 🔍 Workflow
1. Loaded and explored the Iris dataset (150 samples, dropped the ID column)
2. Checked for missing values (none found)
3. Split data into training and testing sets (70/30)
4. Trained a Decision Tree classifier using the **entropy** criterion
5. Evaluated performance using accuracy score
6. Visualized the trained decision tree to interpret the splitting logic

## 📊 Results
- **Accuracy: 97.78%**
- The tree's first split is on **Petal Length ≤ 2.35 cm**, which perfectly separates Setosa from the other two species — matching the well-known biological separability of this feature.

## 📁 Dataset
The classic Iris dataset (150 samples, 3 species, 4 features) — widely available via [Kaggle](https://www.kaggle.com/datasets/uciml/iris) or `sklearn.datasets`.

## 🚀 How to Run
1. Clone this repository
2. Install dependencies: `pip install numpy pandas scikit-learn matplotlib`
3. Open the notebook and run all cells

