# Red Wine Quality Exploratory Data Analysis

## Introduction

This analysis focuses on the **Red Wine Quality dataset**, which contains physicochemical measurements of red wine samples. The purpose of this analysis is to understand how various chemical attributes influence the perceived quality of red wines.

Exploratory Data Analysis was conducted to examine the distribution of different features, detect outliers, analyze relationships between variables, and identify the key attributes that affect wine quality.

## Dataset Overview

The red wine dataset contains:

* 1599 observations
* 12 variables
* All features are numerical

The dataset includes measurements related to acidity, sugar content, sulphur dioxide levels, density, pH levels, and alcohol content.

The target variable **quality** represents a quality rating given by wine experts.

## Quality Distribution Analysis

The analysis shows that the majority of red wines in the dataset fall within **quality ratings of 5 and 6**.

Observations:

* Very few wines have extremely high quality ratings (8 or above).
* Lower quality wines (ratings below 4) are also relatively rare.

Insight:

This indicates that most red wines in the dataset fall within a **moderate quality range**, with relatively few exceptional wines.

## Feature Distribution Analysis

Several features show interesting distribution patterns.

### Alcohol

Alcohol values range approximately between **8% and 14%**, with most wines clustering between **9% and 11%**.

Observation:

Higher alcohol wines appear more frequently among higher quality ratings.

### Residual Sugar

Residual sugar distribution is highly **right-skewed**, indicating the presence of some wines with unusually high sugar levels.

### Volatile Acidity

Volatile acidity shows a moderately wide range across samples.

Insight:

Higher volatile acidity may negatively affect wine taste and quality.

## Correlation Analysis

Correlation analysis reveals several relationships between variables.

Key observations:

* Alcohol shows a **positive correlation with wine quality**
* Volatile acidity shows a **negative correlation with wine quality**
* Density shows a **negative relationship with alcohol content**

Insight:

These relationships suggest that alcohol content is an important factor contributing to higher quality wines, while excessive acidity may reduce quality ratings.

## Outlier Detection

Boxplot analysis revealed the presence of outliers in several features including:

* Residual sugar
* Chlorides
* Sulfur dioxide levels

These outliers represent wines with unusual chemical compositions compared to the rest of the dataset.

## Key Insights

The analysis reveals several important insights:

* Most red wines have **moderate quality ratings**
* Higher alcohol content is associated with **higher wine quality**
* High volatile acidity tends to **reduce wine quality**
* Certain features contain **extreme values that may influence statistical analysis**

## Conclusion

The exploratory analysis highlights the relationships between physicochemical attributes and wine quality. These insights help understand the chemical characteristics associated with higher quality red wines.

This analysis demonstrates how EDA techniques can be used to extract meaningful insights from real-world datasets.