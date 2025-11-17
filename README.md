# Iris Classification Project - Supervised Learning

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://python.org)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.2%2B-orange)](https://scikit-learn.org)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

Complete analysis of the Iris dataset using multiple supervised classification algorithms, including LDA, QDA, SVM, Perceptron, and Decision Trees.

## 🎯 Project Objectives

- Implement and compare multiple classification algorithms
- Perform exploratory data analysis (EDA) with advanced visualizations
- Apply dimensionality reduction techniques (t-SNE)
- Evaluate models using cross-validation
- Interpret results and important features

## 📊 Iris Dataset

The Iris dataset contains 3 classes of 50 instances each, where each class refers to a type of iris plant. It is a classic benchmark in Machine Learning.

**Features:**
- Sepal length (cm)
- Sepal width (cm)
- Petal length (cm)
- Petal width (cm)

**Classes:** Iris Setosa, Iris Versicolour, Iris Virginica

## 🚀 Implemented Features

### 🔍 Exploratory Analysis
- Pairplots with Seaborn
- Dimensional reduction with t-SNE
- Correlation analysis

### 🤖 ML Models Implemented
- **Linear Discriminant Analysis (LDA)**
- **Quadratic Discriminant Analysis (QDA)**
- **Support Vector Machine (SVM)** with RBF kernel
- **Perceptron**
- **Decision Tree Classifier**

### 📈 Evaluation and Metrics
- Cross-validation (5-fold)
- Confusion matrix
- Classification report
- Feature importance
- Decision tree visualization

## 📊 Notable Results

| Model | Average Accuracy | Standard Deviation |
|--------|-----------------|---------------------|
| LDA | 98.00% | ±1.63% |
| QDA | 97.33% | ±1.33% |
| SVM (RBF) | 96.67% | ±2.98% |
| Decision Tree | 95.56% | ±2.98% |
| Perceptron | 72.76% | ±17.31% |

**Best model:** LDA with 98% accuracy

## 🛠️ Technologies Used

- **Python 3.8+**
- **Libraries:** scikit-learn, pandas, numpy, matplotlib, seaborn
- **Algorithms:** LDA, QDA, SVM, Perceptron, Decision Trees, t-SNE
- **Metrics:** Accuracy, Confusion Matrix, Feature Importance

## 📁 Project Structure
```
iris-classification/
├── notebooks/
│ ├── requirements.txt
│ ├── Supervised_classification_TP1_template.ipynb
│ └── iris.csv
├── docs/
│ └── TP1_pdf.pdf # Original report
├── requirements.txt
├── LICENSE
└── README.md
```
## ⚡ Installation and Use


# Clone the repository
```
git clone https://github.com/jmalfaro2019/iris-classification.git
cd iris-classification
```

# Install dependencies
```
pip install -r code/requirements.txt
```
# Run the notebook
```
jupyter notebook notebooks/iris_analysis.ipynb
```

## 📈 Visualizations
- **Pairplot**: Relationships between all features  
- **t-SNE**: 2D projection of the dataset  
- **Decision Tree**: Model structure  
- **Confusion Matrix**: Performance by class  
- **Decision Regions**: Classification boundaries  

---

## 🔍 Key Findings
- **Linear Separability**: *Setosa* is linearly separable, *Versicolor* and *Virginica* are not  
- **Most Important Feature**: Petal length (89.3% importance)  
- **Best Model**: LDA with **98% accuracy**  
- **t-SNE**: Confirms the separability observed in pairplots  

---

## 🌐 Web
🔗 **[View Project on GitHub Pages](https://jmalfaro2019.github.io/Iris-classification/)**

---

## 📄 Full Report
📋 **[Download PDF Report](docs/TP1_pdf.pdf)**

---

## 👨‍💻 Author
**Jose Miguel Alfaro Castillo** — [GitHub](https://github.com/jmalfaro2019) — [LinkedIn](https://www.linkedin.com/in/jose-alfaro-334327291)

---

## 📝 License
This project is licensed under the **MIT License** — see the `LICENSE` file for more details.
