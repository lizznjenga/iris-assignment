# Iris Dataset Analysis and Visualization

This project is part of a Python assignment focused on data analysis and visualization using the **Iris dataset**.

## 🔍 Objective

- Load and explore a dataset using the **pandas** library.
- Perform basic data analysis including descriptive statistics and group-based aggregations.
- Visualize the dataset using **matplotlib** and **seaborn** to uncover patterns and insights.
- Handle missing data and potential errors during file operations.

## 📊 Features

- Dataset loaded from `sklearn.datasets.load_iris()`.
- Data cleaning and exploration (e.g., checking for null values, inspecting data types).
- Grouping by species to compute average petal and sepal measurements.
- Four visualizations:
  - Line chart (trend simulation)
  - Bar chart (average petal length by species)
  - Histogram (distribution of sepal width)
  - Scatter plot (sepal length vs. petal length)

## 📁 Files

- `iris_analysis.py` – Main Python script containing all code
- *(Optional)* `iris_analysis.ipynb` – Jupyter Notebook version, if submitted

## 🧠 Observations

- Setosa species has significantly shorter petal lengths.
- Clear positive correlation between sepal and petal lengths in certain species.
- Sepal width shows a roughly normal distribution.

## ✅ Requirements

- Python 3.x
- pandas
- matplotlib
- seaborn
- scikit-learn

Install dependencies with:

```bash
pip install pandas matplotlib seaborn scikit-learn
