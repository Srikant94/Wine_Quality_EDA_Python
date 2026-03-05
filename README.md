# Wine Quality Exploratory Data Analysis (EDA)

## Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** on the **Wine Quality Dataset**, which contains physicochemical properties of red and white wines. The objective of this analysis is to understand how different chemical attributes influence the **quality ratings of wines**.

Wine quality is influenced by several factors such as acidity levels, alcohol content, sugar concentration, sulphates, and density. Through systematic data exploration and visualization, this project aims to identify patterns, correlations, and insights that explain how these variables relate to wine quality.

The project is divided into three main analytical components:

* Exploratory Data Analysis of **Red Wine Dataset**
* Exploratory Data Analysis of **White Wine Dataset**
* **Comparative Analysis** between Red and White Wines

These analyses help highlight similarities and differences between the two wine types and identify the features that most strongly influence wine quality.

---

## Dataset Information

The datasets used in this project come from the **Wine Quality dataset**, which contains physicochemical tests conducted on different wine samples.

Each dataset includes the following features:

| Feature              | Description                                      |
| -------------------- | ------------------------------------------------ |
| Fixed Acidity        | Concentration of non-volatile acids              |
| Volatile Acidity     | Amount of acetic acid present in wine            |
| Citric Acid          | Natural acid contributing to flavor              |
| Residual Sugar       | Remaining sugar after fermentation               |
| Chlorides            | Salt concentration                               |
| Free Sulfur Dioxide  | Free SO₂ level                                   |
| Total Sulfur Dioxide | Total SO₂ level                                  |
| Density              | Density of wine                                  |
| pH                   | Acidity level                                    |
| Sulphates            | Preservative contributing to microbial stability |
| Alcohol              | Alcohol percentage                               |
| Quality              | Wine quality rating (score between 0–10)         |

The **quality variable** represents the sensory quality of wine evaluated by wine experts.

---

## Objectives of the Analysis

The main objectives of this project include:

* Understanding the distribution of wine quality ratings
* Identifying important physicochemical features affecting wine quality
* Exploring relationships between different wine attributes
* Detecting outliers and unusual observations in the dataset
* Comparing characteristics between red and white wines

---

## Tools and Technologies Used

The following tools were used for the analysis:

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

These tools enabled efficient data manipulation, visualization, and exploratory analysis.

---

## Project Structure

```
wine-quality-eda
│
├── data
│   ├── winequality-red.csv
│   └── winequality-white.csv
│
├── notebooks
│   ├── red_wine_eda.ipynb
│   ├── white_wine_eda.ipynb
│   └── wine_comparison_eda.ipynb
│
├── images
│
└── README.md
```

---

## Key Insights from the Project

Some major insights discovered during the analysis include:

* Most wines in the dataset fall within **quality ratings between 5 and 7**, indicating that the majority of wines are of moderate quality.
* **Alcohol content shows a strong positive relationship with wine quality**, suggesting wines with higher alcohol levels tend to receive higher ratings.
* **Volatile acidity negatively impacts wine quality**, indicating that excessive acidity may reduce perceived quality.
* White wines generally contain **higher residual sugar levels**, making them sweeter compared to red wines.
* Certain chemical properties such as density, acidity, and sulphates show meaningful correlations with wine quality.

---

## Conclusion

Through exploratory data analysis, this project provides insights into how various chemical attributes influence wine quality. Understanding these relationships can help wine producers and analysts gain a deeper understanding of the factors contributing to higher-quality wines.

This project also demonstrates practical skills in **data exploration, visualization, and analytical thinking**, which are fundamental components of data analytics and data science workflows.

---

## Author

Srikant Verma
Data Analytics & Data Science Learner
