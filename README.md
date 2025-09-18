# Wine Dataset Analysis

This repository contains a Jupyter Notebook for analyzing and modeling the [Wine dataset](https://archive.ics.uci.edu/ml/datasets/wine).  
The dataset is widely used for classification tasks, where the goal is to predict the wine cultivar based on chemical analysis of its components.

## 📂 Contents
- `wine_analysis.ipynb` → main notebook with data exploration, preprocessing, and classification models.

## 📊 Dataset
The Wine dataset consists of **178 samples** of wines from three different cultivars.  
Each wine is described by **13 numerical features**, such as:
- Alcohol
- Malic acid
- Ash
- Alcalinity of ash
- Magnesium
- Total phenols
- Flavanoids
- Nonflavanoid phenols
- Proanthocyanins
- Color intensity
- Hue
- OD280/OD315 of diluted wines
- Proline

The target variable indicates the wine cultivar (class 1, 2, or 3).

## ⚙️ Requirements
The notebook is implemented in Python using the following main libraries:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

To install the dependencies, you can run:
```bash
pip install -r requirements.txt
