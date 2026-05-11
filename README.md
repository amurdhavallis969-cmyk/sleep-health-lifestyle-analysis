# Sleep Health & Lifestyle Analysis 😴

> **Tools:** Python · Pandas · Matplotlib · Seaborn  
> **Type:** Exploratory Data Analysis (EDA) + Statistical Analysis

---

## 📌 Project Overview

Analysed a dataset of 400+ individuals to identify lifestyle factors that significantly predict sleep quality.  
Used correlation analysis, statistical visualisations, and regression plots to find which variables — exercise, stress, BMI, and occupation — most strongly influence how well people sleep.

---

## 📊 Dataset

- **Source:** Sleep Health and Lifestyle Dataset (Kaggle)
- **Records:** 400+ individuals
- **Features:** Sleep Duration, Quality of Sleep, Physical Activity Level, Stress Level, BMI Category, Blood Pressure, Heart Rate, Daily Steps, Sleep Disorder

---

## 🔍 Key Findings

- **Stress level** was the strongest negative predictor of sleep quality (correlation: -0.74)
- **Physical activity** showed a moderate positive correlation with sleep duration (+0.42)
- Individuals with **BMI in the Normal range** reported 18% better sleep quality scores than Obese category
- **Occupational stress** (nurses, teachers) linked to higher rates of insomnia vs low-stress roles
- Sleep disorders (Insomnia, Sleep Apnea) were significantly concentrated in the 35–50 age group

---

## 📈 Analysis Performed

| Analysis Type | Description |
|--------------|-------------|
| Univariate EDA | Distribution plots for sleep duration, quality, and stress |
| Bivariate Analysis | Scatter plots and box plots across key variable pairs |
| Correlation Heatmap | Identified top 3 predictors of sleep quality |
| Regression Plot | Stress vs Sleep Quality linear trend |
| Group Comparison | Sleep quality across BMI categories and occupations |

---

## 🛠️ Libraries Used

```python
import pandas as pd          # data loading and manipulation
import numpy as np           # numerical operations
import matplotlib.pyplot as plt  # base visualisations
import seaborn as sns        # statistical plots and heatmaps
```

---

## 💡 Skills Demonstrated

- End-to-end EDA workflow (load → clean → explore → visualise → conclude)
- Handling missing values and categorical encoding
- Correlation analysis and feature significance interpretation
- Clear visual storytelling with annotated charts

---

## 📁 Repository Structure

```
📂 Sleep-Health-Analysis
 ┣ 📓 sleep_health_analysis.ipynb   ← Main Jupyter Notebook
 ┣ 📄 sleep_health_lifestyle.csv    ← Dataset
 ┣ 🖼️ plots/
 ┃  ┣ correlation_heatmap.png
 ┃  ┣ stress_vs_sleep.png
 ┃  ┗ bmi_vs_quality.png
 ┗ 📄 README.md
```

---

## 🚀 How to Run

```bash
# Clone the repo
git clone https://github.com/amurdhavallis969-cmyk/sleep-health-analysis.git

# Install dependencies
pip install pandas numpy matplotlib seaborn jupyter

# Launch notebook
jupyter notebook sleep_health_analysis.ipynb
```

---

## 🖼️ Sample Visualisations

*(Upload your heatmap and scatter plots here by dragging images into GitHub)*

---

*Part of my data analytics portfolio. Connect with me on [LinkedIn](https://linkedin.com/in/amurdhavalli-s-10524938a)*
