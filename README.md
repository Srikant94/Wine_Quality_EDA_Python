Wine Quality Exploratory Data Analysis

- Two datasets are included, related to red and white vinho verde wine samples, from the north of Portugal. The goal is to model wine quality based on physicochemical tests. (see [Cortez et al., 2009], http://www3.dsi.uminho.pt/pcortez/wine/).

- The two datasets are related to red and white variants of the Portuguese "Vinho Verde" wine. For more details, consult: http://www.vinhoverde.pt/en/ or the reference [Cortez et al., 2009].  Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.).

- These datasets can be viewed as classification or regression tasks.  The classes are ordered and not balanced (e.g. there are many more normal wines than excellent or poor ones). Outlier detection algorithms could be used to detect the few excellent or poor wines. Also, we are not sure if all input variables are relevant. So it could be interesting to test feature selection methods.

- Input Variables based on physicochemical tests :-

1 - fixed acidity
2 - volatile acidity
3 - citric acid
4 - residual sugar
5 - chlorides
6 - free sulfur dioxide
7 - total sulfur dioxide
8 - density
9 - pH
10 - sulphates
11 - alcohol

- Output variable (based on sensory data):

12 - quality (score between 0 and 10)

- Description: This project performs Exploratory Data Analysis on Red and White Wine Quality datasets to understand how physicochemical properties influence wine quality ratings.

- Objectives:
1. Explore dataset distributions
2. Identify correlations
3. Detect outliers
4. Compare red and white wines

- Tools Used:
1. Python
2. Pandas
3. Seaborn
4. Matplotlib
5. Scikit-learn

- Project Components:
1. Red Wine EDA
2. White Wine EDA
3. Comparative Analysis

Red Wine - Key Insights
1. Most red wines have quality 5–6
2. Alcohol positively impacts quality
3. Volatile acidity negatively impacts quality
4. Several features contain outliers

White Wine - Key Insights
1. Most white wines have quality 6–7
2. Residual sugar shows large variability
3. Alcohol positively correlates with quality
4. Sulphates show moderate positive influence

Comparison - Key Findings
1. White wines tend to have higher sugar levels
2. Red wines tend to have higher acidity

Alohol positively influences quality for both wine types

White wines appear to have slightly higher average quality ratings# Wine_Quality_EDA_Python
