# Titanic EDA

This project contains an exploratory data analysis of the `Titanic-Dataset.csv` dataset. The goal of the notebook was to understand the structure of the dataset, inspect the main features, check data quality, and identify patterns related to passenger survival.

The analysis starts by loading the dataset with `pandas` and viewing the first few rows to understand the available columns, such as passenger class, sex, age, fare, family information, embarkation point, and survival status. After that, I generated summary statistics to get a quick overview of the numerical columns and also checked median values and missing values to understand the distribution of the data and spot incomplete fields.

To explore the dataset visually, I used histograms and boxplots for numerical features like `Age`, `Fare`, `SibSp`, and `Parch`. These plots help show the spread of the data, the concentration of values, and possible outliers. I also used a correlation heatmap and pairplot to examine relationships between important numeric variables and to see how some of them may be associated with survival.

The notebook also focuses on identifying trends and patterns using `seaborn` visualizations. Count plots and bar plots were used to compare survival across groups such as passenger class and sex. Additional plots were used to better understand age distribution, fare distribution, and family-related features.

Key insights from the analysis:

- most passengers were between 20 and 40 years old
- most fares were concentrated on the lower end, with some higher-value outliers
- a large number of passengers traveled in third class
- female passengers had a much higher survival rate than male passengers
- passengers in first class were more likely to survive than those in lower classes
- most passengers were traveling without siblings, spouses, parents, or children

Overall, this notebook serves as a basic EDA project that summarizes the Titanic dataset and highlights the most important patterns before any feature engineering or predictive modeling for Task2 of the internship program.

Tools used: `Python`, `pandas`, `matplotlib`, and `seaborn`.
