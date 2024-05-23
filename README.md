# Country Happiness Ranking Research

## Overview

The project "Country Happiness Ranking Research" is aimed at identifying factors that influence the level of happiness of the population in different countries and understanding the dynamics of this phenomenon over time. By analyzing various social, economic, cultural and political factors, the project aims to identify the key influential variables that determine the level of happiness of countries. Based on the data and results of the study, recommendations can be developed to improve social policy, economic development and other areas aimed at improving the quality of life of the population and creating favorable conditions for its development. 

# Milestone 1: 
## <font color="blue">Identification of the problem</font>

### **Research questions**:
*	What factors are most correlated with the overall level of happiness in countries?
*	Is there a link between economic indicators (e.g., GDP per capita) and happiness?
*	Is there a relationship between social indicators (e.g., trust) and happiness?
*	What is the impact of quality of life (e.g., access to education and health care) on overall happiness?
*	Is it possible to predict the level of happiness of countries using machine learning models based on various factors?

Researching these questions can help to better understand what factors influence the happiness of the population of countries and how this knowledge can be used to improve the quality of life.


## <font color="blue">The main purposes and uses of Country Happiness Ranking Research include:</font>

* **Assessment of the quality of life**: Happiness rankings allow us to assess the overall level of life satisfaction and happiness of the population in different countries.This is important for understanding how satisfied people are with their lives and what factors affect their well-being.

* **Comparison between countries**: Happiness rankings allow you to compare the level of happiness and well-being between different countries. This can help identify differences in living conditions, economic conditions, social policies, and other factors between countries.

* **Assessing the impact of policies and programs**: Happiness rankings can serve as an indicator of the effectiveness of social programs, economic policies and other initiatives in the area of well-being and life satisfaction. It helps to identify which measures lead to to improve the quality of life and happiness of the population.

* **Development of improvement strategies**: Analyzing happiness rankings can help develop strategies and programs to improve quality of life and life satisfaction in different countries. It allows to identify key aspects that should be improved to achieve higher levels of well-being.


# Milestone 2: 

## <font color="blue">Data Collection</font>


### Non-Technical Explanation of Domain Modeling

In this project, domain modeling is like creating a map to help us navigate the complex landscape of global happiness levels. It's a visual guide, like a map, that helps us understand how economic prosperity, social support systems, health indicators, and personal freedoms influence the happiness of people in different parts of the world.

###  Data Collection and Cleaning Scripts

For transparency and replication, I provide all scripts for data collection and cleaning, covering the entire process, including data partitioning.

### Research Work
Engaged in Data Science research, I focus on identifying deep patterns and trends that shed light on what makes people happy around the world. Through rigorous analysis and innovative approaches, I aim to make a significant contribution to understanding and promoting happiness around the world.

**_Be aware that the full description of this milestone you can find by refer to [README](./milestone/milestone_2/README.md)_**

# Milestone 3: 

## [Data Analysis](./milestone/milestone_3)

**_Be aware that the full description of this milestone you can find by refer to [README](./milestone/milestone_3/README.md)_**

### `Non-technical explanation of our findings`

This analysis of the Country Happiness Ranking Research dataset revealed significant insights into the factors that influence happiness across various countries. By examining economic, social, and institutional indicators, I observed how these variables impact the overall happiness and well-being of populations globally.

### `Key Findings`

The overall model explain a significant proportion of the variance (R-squared = 0.798) and the  model generalizes well to new data, as the R^2 on the test data (0.8119) and the R^2 on the training data (0.7898) are very close to each other. This indicates that the model is not overfitted and has good predictive power.

### `Technical description of analysis`

Results of the data analysis conducted using Jupyter Notebook can be found [**here**](/milestone/milestone_3/analysis.ipynb).

### `Technical explanation of our findings`

    The analysis was done in Python.

1. **Country Happiness Ranking Analysis:**

   - **Social support** and **GDP per capita** are the most important factors in this model, emphasizing the importance of social ties and support for well-being..
   - **The happiest countries** are mostly located in Europe. Finland, Denmark, Iceland, the Netherlands, Sweden, Norway, Switzerland, and Luxembourg are all located in Europe.

   Israel, also among the happiest countries, is located in the Middle East.

   - **The least happy countries** are mostly located in Africa. These are Afghanistan, Lebanon, Sierra Leone, Zimbabwe, Congo (Kinshasa), Botswana, Malawi, Comoros, Tanzania and Zambia.

   Afghanistan and Lebanon are located in Asia, which indicates that regional conflicts and political instability can have a significant impact on the level of happiness of the population.

2. **Relationship Between Economic Prosperity and Ladder score:**
   - Countries with higher Logged GDP per capita also have high Ladder scores, which indicates a correlation between economic well-being and happiness. For example, Luxembourg (Logged GDP per capita = 11,660) has a Ladder score of 7.228, and Denmark (Logged GDP per capita = 10,962) has a Ladder score of 7.586. However, there are exceptions where countries with relatively high Logged GDP per capita have lower happiness scores, for example, Singapore (Logged GDP per capita = 11,571) has a Ladder score of 6.587, which is lower than some other rich countries.

   - The poorest countries tend to have very low Ladder scores, indicating that economic hardship can have a strong impact on overall happiness. For example, Afghanistan (Logged GDP per capita = 7.324) has the lowest Ladder score of 1.859.
   However, some poor countries, such as Mozambique (Logged GDP per capita = 7.116) with a Ladder score of 4.954, show that even with a low economic level, there may be other factors that support a relatively high level of happiness.

3.  **The relationship between social support and happiness**:

    - **High level of social support:**

    All of the countries in the top 10 by Ladder Score have a high level of social support. The values of social support for these countries are in a narrow range from 0.879 to 0.983, indicating that high levels of social support are one of the key factors contributing to high levels of happiness.

    The high values of social support in countries with high levels of happiness confirm the correlation between these two indicators. This means that people in countries with high levels of social support feel happier.

    - **Distribution of happiness and social support**:

    The countries with the highest happiness scores (Finland, Denmark, Iceland) also have some of the highest social support scores. This suggests that social support is an important factor in achieving high levels of happiness.

    - **Comparison between countries**:

     Finland, which has the highest level of happiness (7.804), also has a high level of social support (0.969). This reflects the general trend that countries with high levels of happiness provide their citizens with a high level of social support.

     Luxembourg has the lowest level of social support among the top 10 countries (0.879), but is still among the happiest countries. This may indicate that while social support is an important factor, other aspects such as economic development and freedom also have a significant impact on happiness.
   

_For a detailed analysis, refer to the [Full Project Analysis](./milestone/milestone_3/README.md) in the project repository._


