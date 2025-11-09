# Iris Classification Project - Supervised Learning

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://python.org)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.2%2B-orange)](https://scikit-learn.org)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

Análisis completo del dataset Iris utilizando múltiples algoritmos de clasificación supervisada, incluyendo LDA, QDA, SVM, Perceptron y Árboles de Decisión.

## 🎯 Objetivos del Proyecto

- Implementar y comparar múltiples algoritmos de clasificación
- Realizar análisis exploratorio de datos (EDA) con visualizaciones avanzadas
- Aplicar técnicas de reducción de dimensionalidad (t-SNE)
- Evaluar modelos mediante validación cruzada
- Interpretar resultados y características importantes

## 📊 Dataset Iris

El dataset Iris contiene 3 clases de 50 instancias cada una, donde cada clase se refiere a un tipo de planta iris. Es un benchmark clásico en Machine Learning.

**Características:**
- Sepal length (cm)
- Sepal width (cm) 
- Petal length (cm)
- Petal width (cm)

**Clases:** Iris Setosa, Iris Versicolour, Iris Virginica

## 🚀 Características Implementadas

### 🔍 Análisis Exploratorio
- Pairplots con Seaborn
- Reducción dimensional con t-SNE
- Análisis de correlaciones

### 🤖 Modelos de ML Implementados
- **Linear Discriminant Analysis (LDA)**
- **Quadratic Discriminant Analysis (QDA)**
- **Support Vector Machine (SVM)** con kernel RBF
- **Perceptron**
- **Decision Tree Classifier**

### 📈 Evaluación y Métricas
- Validación cruzada (5-fold)
- Matriz de confusión
- Reporte de clasificación
- Importancia de características
- Visualización de árboles de decisión

## 📊 Resultados Destacados

| Modelo | Precisión Media | Desviación Estándar |
|--------|-----------------|---------------------|
| LDA | 98.00% | ±1.63% |
| QDA | Por evaluar | - |
| SVM (RBF) | Por evaluar | - |
| Decision Tree | 95.56% | - |

**Mejor modelo:** LDA con 98% de precisión

## 🛠️ Tecnologías Utilizadas

- **Python 3.8+**
- **Librerías:** scikit-learn, pandas, numpy, matplotlib, seaborn
- **Algoritmos:** LDA, QDA, SVM, Perceptron, Decision Trees, t-SNE
- **Métricas:** Accuracy, Confusion Matrix, Feature Importance

## 📁 Estructura del Proyecto
```
iris-classification/
├── code/
│ ├── iris_analysis.py # Análisis principal
│ ├── model_comparison.py # Comparación de modelos
│ └── visualization.py # Funciones de visualización
├── docs/
│ └── TP1_pdf.pdf # Reporte original
├── images/ # Visualizaciones generadas
├── requirements.txt
├── LICENSE
└── README.md
```
## ⚡ Instalación y Uso


# Clonar el repositorio
```
git clone https://github.com/jmalfaro2019/iris-classification.git
cd iris-classification
```
# Instalar dependencias
```
pip install -r requirements.txt
```
# Ejecutar análisis completo
```
python code/iris_analysis.py
```

## 📈 Visualizaciones
- **Pairplot**: Relaciones entre todas las características  
- **t-SNE**: Proyección 2D del dataset  
- **Árbol de Decisión**: Estructura del modelo  
- **Matriz de Confusión**: Rendimiento por clase  
- **Regiones de Decisión**: Fronteras de clasificación  

---

## 🔍 Hallazgos Clave
- **Separabilidad Lineal**: *Setosa* es linealmente separable, *Versicolor* y *Virginica* no  
- **Característica Más Importante**: *Petal length* (89.3% de importancia)  
- **Mejor Modelo**: LDA con **98% de precisión**  
- **t-SNE**: Confirma la separabilidad observada en pairplots  

---

## 🌐 Demo en Vivo
🔗 Ver Proyecto en **GitHub Pages**

---

## 📄 Reporte Completo
📋 Descargar **Reporte PDF**

---

## 👨‍💻 Autor
**Jose Miguel Alfaro Castillo** — [GitHub]((https://github.com/jmalfaro2019) — [LinkedIn](https://www.linkedin.com/in/jose-alfaro-334327291)

---

## 📝 Licencia
Este proyecto está bajo la **Licencia MIT** — ver el archivo `LICENSE` para más detalles.
