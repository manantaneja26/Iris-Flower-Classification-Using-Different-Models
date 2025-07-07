# Iris‑Flower‑Classification‑Using‑Different‑Models

A machine learning project that classifies iris flowers into species using classic supervised models. Focuses on benchmarking accuracy and simplicity across different algorithms on the Iris dataset.

## 🔍 Description

This project loads the well-known Iris flower dataset and trains several classification models to predict species based on features like petal length and sepal width. It compares the performance of models like KNN, SVM, Decision Trees, and Logistic Regression using accuracy metrics and visualization.

## 🛠️ Techniques

- **Supervised classification** on a structured dataset with labeled examples.
- **Scikit-learn pipelines** for model training, testing, and evaluation. [See docs](https://scikit-learn.org/stable/tutorial/statistical_inference/supervised_learning.html)
- **Data visualization** using seaborn and matplotlib for pair plots and decision boundary plots.
- **Cross-validation** to evaluate model robustness on unseen data.

## 📦 Technologies & Libraries

- [scikit-learn](https://scikit-learn.org/) – used for model training, evaluation, and data splitting.
- [pandas](https://pandas.pydata.org/) – dataset manipulation and analysis.
- [matplotlib](https://matplotlib.org/) and [seaborn](https://seaborn.pydata.org/) – data and result visualization.
- Jupyter notebooks used to compare model performance and show workflow step-by-step.

## 🗂️ Project Structure

```
/
├── data/
├── models/
├── notebooks/
├── plots/
├── src/
└── README.md
```

- **data/** – stores the Iris dataset (CSV or other formats).
- **models/** – saved model files for reuse or evaluation.
- **notebooks/** – Jupyter notebooks comparing different ML algorithms.
- **plots/** – exported graphs and visualizations.
- **src/** – Python scripts for loading data, training models, and generating results.
