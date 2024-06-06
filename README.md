Name : CHINTHA VARSHITHA 
ID   : CTO9WD63
Domain : Data science
Duration : 4 week from 10th may 2024 to 10th june 2024
Mentor  : Sravani Gouni
Description : 
Exploratory Data Analysis (EDA) of the Titanic Dataset
Objective: The objective of this project is to perform an in-depth exploratory data analysis (EDA) of the Titanic dataset using popular Python libraries such as pandas, numpy, matplotlib, and seaborn. The goal is to uncover the characteristics, distributions, correlations, and outliers in the data, and visualize the findings using histograms, scatter plots, and heatmaps to gain valuable insights into the data.
Dataset: The Titanic dataset is a well-known dataset that contains information about passengers who boarded the RMS Titanic, including their demographics, ticket details, and survival status. The dataset consists of 12 features and 891 observations.
Methodology:

    Data Loading and Cleaning: Load the Titanic dataset into a pandas dataframe and perform initial data cleaning, including handling missing values and data type conversions.
    Data Characteristics: Use pandas to generate summary statistics, including mean, median, mode, and standard deviation, to understand the central tendency and variability of the data.
    Data Distributions: Use histograms and density plots to visualize the distribution of numerical features, such as Age and Fare, and categorical features, such as Sex and Pclass.
    Correlation Analysis: Calculate the correlation matrix using pandas and visualize it using a heatmap to identify relationships between features.
    Outlier Detection: Use box plots and scatter plots to identify outliers in the data, which can be indicative of errors or unusual patterns.
    Visualization: Use matplotlib and seaborn to create informative and interactive visualizations, including histograms, scatter plots, and heatmaps, to communicate the findings effectively.

Expected Outcomes:

    A comprehensive understanding of the Titanic dataset's characteristics, including summary statistics and data distributions.
    Identification of correlations between features, which can inform feature engineering and model selection.
    Detection of outliers and anomalies in the data, which can be used to improve data quality and model performance.
    Informative and interactive visualizations that effectively communicate the findings and insights gained from the EDA.

By performing a thorough EDA of the Titanic dataset, this project aims to demonstrate the importance of exploratory data analysis in understanding the characteristics of a dataset and informing subsequent machine learning tasks.

Conclusion :

In this project, we conducted a thorough Exploratory Data Analysis (EDA) on the Titanic dataset using Python libraries such as pandas, numpy, matplotlib, and seaborn. Our objective was to gain a deeper understanding of the dataset's characteristics, distributions, correlations, and outliers, thereby uncovering valuable insights that could inform further analysis or modeling.
Dataset Overview:

    We loaded and examined the Titanic dataset, which includes 891 entries and 12 columns, covering both numerical and categorical data.
    Summary statistics and information about data types and missing values were obtained using info() and describe() methods. Notably, the Age, Cabin, and Embarked columns contained missing values, with Cabin having a significant proportion of missing data.

Missing Values:

    Identifying missing values is crucial for preprocessing steps. We found that 177 entries were missing Age values, 687 entries were missing Cabin values, and 2 entries were missing Embarked values. Handling these missing values appropriately is essential for ensuring the accuracy and reliability of subsequent analyses.

Data Distributions:

    Histograms for numerical features (Age, Fare, SibSp, Parch) revealed their distribution patterns. For example, Fare displayed a right-skewed distribution, indicating that most passengers paid lower fares.
    Bar plots for categorical features (Sex, Pclass, Embarked, Survived) highlighted the distribution of passengers across different categories. For instance, there were more male passengers than female, and the majority of passengers embarked from port 'S'.

Correlation Analysis:

    A heatmap of the correlation matrix showed relationships between numerical features. Notably, Pclass and Fare were negatively correlated, indicating that higher class tickets were associated with higher fares.

Scatter and Box Plots:

    Scatter plots, such as Age vs Fare colored by survival status, provided visual insights into the relationship between these variables and survival.
    Box plots identified potential outliers in features like Fare and Age.

Insights:

    Key insights included the influence of Pclass and Sex on survival rates, with higher survival rates for women and first-class passengers.
    Outliers and missing values were identified, which are crucial for preprocessing steps in predictive modeling.

Overall, this EDA provided a comprehensive understanding of the Titanic dataset, laying the foundation for more advanced analysis and predictive modeling
