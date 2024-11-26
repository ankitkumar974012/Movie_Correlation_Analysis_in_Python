# Movie_Correlation_Analysis_in_Python

# Movie Correlation Analysis in Python
**Author: Ankit Kumar**

**Date:** November 2024

### Introduction
In this project, I explored the application of data analysis techniques using Python to uncover correlations within a dataset from the movie industry. This project is part of my Data Analyst Portfolio series, aimed at demonstrating the process of analyzing relationships between different variables such as budget, revenue, and other attributes of movies. I leveraged popular **Python libraries like Pandas, Seaborn, and Matplotlib** for data analysis and visualization. My ultimate goal was to identify which factors have the most significant impact on a movie's gross revenue.

### Objective
The primary objective of this project was to conduct a correlation analysis on a movie dataset to discover key drivers of a movie's financial performance. By identifying these key factors, I aimed to provide actionable insights that could help in decision-making processes related to movie production and marketing.

### Steps Taken to Complete the Project
1. **Data Import and Setup**: I set up the Python environment and imported the necessary libraries. Using Jupyter Notebook, I leveraged Pandas for data manipulation, Numpy for numerical operations, and Seaborn/Matplotlib for data visualization. The dataset used in this project was sourced from Kaggle and contained various attributes of movies such as budget, company, genre, gross revenue, release date, etc.

2. **Data Cleaning and Preparation**: Data cleaning was a crucial step in my analysis. I checked for missing values, removed duplicates, and ensured that all columns were in the correct data type format. For example, I converted the budget and gross revenue columns from float to integer for consistency. Additionally, I created new features where necessary, such as extracting the release year from the release date.

3. **Exploratory Data Analysis (EDA)**: During the exploratory data analysis phase, I used various visualizations to identify patterns and relationships between variables. For example, I used scatter plots to visualize the relationship between budget and gross revenue. I also explored the distribution of other numerical variables and examined the frequency of categorical variables.

4. **Correlation Analysis**: A significant part of this project involved correlation analysis, where I analyzed how various features correlated with each other. I used methods like Pearson, Spearman, and Kendall to determine the correlation strength. It was discovered that budget and votes are highly correlated with gross revenue, indicating that higher budgets and audience engagement lead to better financial performance.

5. **Data Visualization**: Visualizations were crucial in my analysis. I used various plots like scatter plots, regression plots, and heatmaps to gain insights. These visualizations helped in understanding the correlations and drawing meaningful conclusions from the data.

### Conclusion
The analysis provided insightful findings, revealing that budget and votes have a strong positive correlation with movie gross revenue. This suggests that investing in a higher budget and gaining audience engagement can significantly impact a movie's financial success.
