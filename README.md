# Data-science-Iris-Flower-Classification-
# 🌸 Iris Flower Classification

## 📌 Overview
Brief introduction to the project and the Iris dataset. What this project does, and why it's useful.

## 📁 Project Structure
List of important files and what they contain:
- `IRIS.csv`: The dataset
- `iris.ipynb`: Jupyter Notebook with code for loading, visualizing, and classifying data
- `README.md`: This file
- `correlation_heatmap.png`, `feature_boxplots.png`: Saved visualizations

## 📊 Dataset Description
A short explanation of the dataset and its columns:
- `sepal_length`
- `sepal_width`
- `petal_length`
- `petal_width`
- `species` (Setosa, Versicolor, Virginica)

## 🖼️ Visualizations
- Pair plots to understand relationships
- Scatter plots for specific feature comparisons
- Boxplots showing class separation
- Correlation heatmap to explore relationships between features

## 🔍 Feature Importance
- Discussion of which features are most useful
- Highlight: **Petal Length** is most discriminative
- Include saved image references like:
  - `feature1.png.png`
  - `feature2.png.png`
  - `feature3.png.png`
  - `Heatmap.png.png`

## 🧠 Machine Learning Models
### 1. Neural Network (Keras)
- Preprocessing: Scaling + One-hot encoding
- Architecture: 2 hidden layers + softmax output
- Accuracy and performance

### 2. Decision Tree (Scikit-learn)
- Label encoding
- Criterion used (e.g., entropy)
- Accuracy + Confusion matrix

## 🧪 Evaluation
- Accuracy scores
- Classification reports
- Confusion matrices

## 🚀 Getting Started
How to run the project:
1. Install dependencies
2. Load Jupyter Notebook
3. Run cells in order

### Requirements
```bash
pip install pandas numpy matplotlib seaborn scikit-learn tensorflow
