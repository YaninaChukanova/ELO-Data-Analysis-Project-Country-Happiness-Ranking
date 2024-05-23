# Data Analysis using CSV Files

## Description

This project involves the analysis of data from  CSV file containing information 

## Used File:
1. ** Data_for_Project:** [`Data_for_Project.csv`](../../data/Data_for_Project.csv)

   - Structure: Country name, Ladder score, Logged GDP per capita, Social support, Healthy life expectancy, Freedom Index, The World Giving Index, Corruption Perceptions Index. 


## Technical Explanation of Findings:

  The analysis involved several steps to ensure a comprehensive understanding of the data and its implications:

1. **Preliminary Data Analysis**

   - Loading and Checking Data:
**Data_for_Project:** [`Data_for_Project.csv`](../../data/Data_for_Project.csv)  
# Load the cleaned CSV file
cleaned_file_path = "../../data/Cleaned_Data_for_Project.csv"
df1 = pd.read_csv(cleaned_file_path, delimiter=';')

   - Structure: Country name, Ladder score, Logged GDP per capita, Social support, Healthy life expectancy, Freedom Index, The World Giving Index, Corruption Perceptions Index.  Initial data import and inspection to ensure correctness and completeness.

   - Data Cleaning: Addressing missing values and anomalies to prepare the dataset for analysis.

   - First Data Review: Basic statistical characteristics and a check for missing values to understand data distribution.

2. **Correlation Study**

   - Correlation Matrix: Calculation of correlations between different factors and the happiness score to identify key relationships

   [Code and conclusions HERE](analysis.ipynb#Correlation-matrix-and-distribution-plots)

3. **Data Distribution**

   - Box Plot Analysis: Visualization of quantitative data distribution to reveal main statistical characteristics and outliers.
   [Code and conclusions HERE](analysis.ipynb#Data-distribution-plots)

4. **Factor Impact Analysis on Happiness Rating**

   - Pie Chart: Displaying the impact of each indicator on the "Ladder score" to understand their relative importance.
   [Code and conclusions HERE](analysis.ipynb#Analysis-of-factors-influencing-the-happiness-ranking)

   
   
5. **Analysis of the Happiest Countries**

   - Top 20 Happiest Countries Graph: Visualization of six key factors contributing to the happiness of the top 20 countries.
   [Code and conclusions HERE](analysis.ipynb#Top-20-Happiest-Countries:-Six-factors)

   - Happiest and Unhappiest Countries in 2023 Barplot: Comparing the happiest and least happy countries.
   [Code and conclusions HERE](analysis.ipynb#-Happiest-and-Unhappiest-Countries-in-2023)

   - Generous and Ungenerous Countries in 2023 Barplot: Examining the generosity index of the happiest and least happy countries.
   [Code and conclusions HERE](analysis.ipynb#Generous-and-Ungenerous-Countries-in-2023)

6. **Health and Corruption Analysis**

   - Top 10 Countries with Highest and Lowest Healthy Life Expectancy Barplots: Analyzing health expectations across countries.
   [Code and conclusions HERE](analysis.ipynb#Top-10-countries-with-the-highest-healthy-life-expectancy)

   - Top 10 Countries with Highest/Lowest Corruption Perceptions Index Barplots: Investigating the impact of corruption perceptions on      happiness.
   [Code and conclusions HERE](analysis.ipynb#Top-10-countries-with-the-highest-/-lowest-Corruption-Perceptions-Index)


7. **Wealth Analysis**

   - Richest and Poorest Countries by Logged GDP per Capita Barplot: Exploring the economic disparity.
   [Code and conclusions HERE](analysis.ipynb#Richest-and-Poorest-Countries-by-Logged-GDP-per-capita)

   - Top 10 Countries by Ladder Score and Freedom Index: Comparing freedom and happiness levels.
    [Code and conclusions HERE](analysis.ipynb#Top-10-countries-by-Ladder-Score-and-Freedom-Index)

   - Top 10 Countries by Ladder Score and Social support: Comparing social support and happiness levels.
   [Code and conclusions HERE](analysis.ipynb#Top-10-countries-by-Ladder-Score-and-Social-support)

   - Comparison of Top 10 Countries by Logged GDP per Capita and Ladder Score Barplot: Correlating wealth with happiness.
    [Code and conclusions HERE](analysis.ipynb#Comparison-Top-10-the-best-and-the-worst-countries-in-terms-of-Logged-GDP-per-capita-and-Ladder-score)
   

8. **Geographical Analysis**

   - World Happiness Score Map 2023: Geographical visualization of happiness scores across the globe.
   [Code HERE](analysis.ipynb#Geographical-analysis)

9. **Regression Analysis**
 [Code and conclusions HERE](analysis.ipynb#Linear-Regression-Analysis-and-Outlier-Detection-between-Logged-GDP-per-capita-and-Ladder-score)


   - Scatter Plot with Trend Line: Visualizing the relationship between key indicators and happiness with a fitted trend line.

   - R² Calculation: Assessing the goodness of fit for our regression model.

   - Model Residuals Check: Identifying systematic errors in predictions by analyzing residuals.

10. **Feature Importance Analysis**

   - Feature Importance: Determining the influence of various factors on happiness using regression coefficients.
     [Code HERE](analysis.ipynb#Analysis-of-the-importance-of-characteristics)

11. **Model Improvement**  
 [Code and conclusions HERE](analysis.ipynb#Trying-different-regression-models)

   - Trying Different Regression Models: Experimenting with polynomial regression and regularized regression (Ridge, Lasso).

   - Regularized Regression: Implementing Ridge and Lasso regression to enhance model performance.
   
   - Cross-Validation: Evaluating model robustness and accuracy through cross-validation techniques.

