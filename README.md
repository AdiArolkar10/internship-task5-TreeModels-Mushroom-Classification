📌 Note: This task is part of a structured internship to reinforce basic ML skills. It’s not meant to reflect my current skill level or portfolio quality.

# 🍄 Mushroom Classification – Tree Models

This project uses **Decision Tree** and **Random Forest** classifiers to predict whether a mushroom is **edible** or **poisonous**, based on the [Mushroom Classification Dataset](https://www.kaggle.com/datasets/uciml/mushroom-classification).

The goal is to:
- Learn and apply tree-based models in Machine Learning.
- Compare Decision Tree vs Random Forest performance.
- Visualize model decisions and feature importance.

---

## 📂 Dataset
The dataset is already included in this repository as `mushrooms.csv`.  
It contains 8124 mushroom samples with 22 categorical features.

**Target Variable:**
- `class`: `e` = edible, `p` = poisonous

---

## ⚙️ Features
- **Train/Test Split** – 80/20
- **Decision Tree** – controlled max depth to avoid overfitting
- **Random Forest** – ensemble method with 100 estimators
- **Visualizations**:
  - Decision Tree diagram
  - Feature importance bar chart
- **Cross-validation** for performance evaluation

---

## 📊 Results (Example)
| Model            | Accuracy |
|------------------|----------|
| Decision Tree    | 1.000    |
| Random Forest    | 1.000    |

*Note: Due to dataset simplicity, models can achieve perfect accuracy.*

---

## 🚀 How to Use

### **1. Open in Google Colab**
1. Click here to open the notebook: **[Colab Link]()** *(Add your Colab link after upload)*

---

### **2. Run the Notebook**
You can use the **dataset already in this repo** without uploading manually:
```python
import pandas as pd

# Load dataset directly
df = pd.read_csv('mushrooms.csv')
print(df.head())
