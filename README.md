# plp_week_8# 🌸 Iris Dataset Analysis

This project demonstrates a basic data analysis workflow using the **Iris dataset**, one of the most famous datasets in machine learning and statistics.

## 📁 Files Included

- `iris_dataset_analysis.ipynb` — Jupyter notebook with all data analysis, visualizations, and observations.
- `README.md` — This file, explaining the contents and purpose of the project.

## 🧠 Objectives

- Load and explore a dataset using **pandas**
- Perform basic statistical analysis
- Visualize the dataset using **matplotlib** and **seaborn**

## 📊 Dataset Description

The **Iris dataset** is sourced from the `sklearn.datasets` module and contains 150 samples of iris flowers with the following features:

- Sepal length (cm)
- Sepal width (cm)
- Petal length (cm)
- Petal width (cm)
- Species (Setosa, Versicolor, Virginica)

## 🔍 What You'll See

### Data Exploration
- View structure and check for missing values
- Summary statistics using `.describe()`
- Grouping data by species

### Visualizations
- **Line Chart**: Average sepal length per species
- **Bar Chart**: Average petal length per species
- **Histogram**: Distribution of sepal width
- **Scatter Plot**: Sepal length vs petal length by species

### Key Observations
- Setosa flowers have shorter petals and wider sepals.
- Versicolor and Virginica species overlap on some metrics.
- Sepal length is positively correlated with petal length.
- Sepal width follows an approximately normal distribution.

## 🛠️ Requirements

- Python 3.6+
- Jupyter Notebook
- pandas
- matplotlib
- seaborn
- scikit-learn

You can install all dependencies using:

```bash
pip install pandas matplotlib seaborn scikit-learn
