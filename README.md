# Capstone_Nss
# Capstone Project: Analyzing Obesity Prevalence and its Influenmcing Factors Across Countries

## Table of Contents
1. [Motivation](#Motivation)
2. [Questions](#Questions)
3. [Normalizing the Data](#Normalizing the Data)
4. [Problems and Hurdles](#Problems and Hurdles)
4. [Technologies](#Technologies)
5. [Data Sources](#Data Sources)
6. [Conclusion](#Conclusion)


# Motivation 
Obesity has become a significant public health issue worldwide, with increasing rates observed in both high income and low income countries. This project aims to explore the factors contributing to obesity prevalence across countries over different time periods. By analyzing key indicators such as GDP per capita, daily protein supply, life expectancy, physical activity, meat consumption, monthly income, and population, this project provides insights into how socioeconomic factors influence obesity rates and can help inform public health policies. Understanding global trends in obesity prevalence can promote healthier lifestyles and improve public health outcomes.

# Questions
1.Which countries had the greatest increase in obesity rates over time, and which had a decrease?
2.Which country had the lowest obesity rates in overall?
3.Which countries had higher obesity rates in 2015 compared to 1990?
4.How does the distribution of obesity prevalence differ between 2000 and 2015?
5.Which five countries had the highest obesity rates in 2015?
6.What are the Top five and Bottom five countries for each Year from 1990 to 2016?
7.How do obesity prevalence, GDP per capita, daily protein supply, life expectancy, daily calorie supply, and population compare across the years 1990, 2000, and 2010?
8.Is there any correlation between obesity prevalence and factors such as GDP per capita, Daily protein supply, Life expectancy, Population?
9.How does obesity prevalence Correlate with various socioeconomic factors like Income, Meat consumption, and Average daily steps?

# Normalizing the Data
 1.Handling missing data : Miising values are handled through .dropna method 
 2.Based on the main dataset i have included years starting from 1990 to 2016 only
 3.checked the data types, and changed the data types based on the priorities

# Problems and Hurdles
I was having trouble dowloading the data which has infomation about the deaths by Obesity prevalence, and also i had other data with information about the three countries i.e.,Peru, Mexico and Colombia. Thought of including this in my Analysis, but there are no matching Obesity Prevalence recorded for the main data set that i have, and ended up not working with that dataF

# Technologies
1.Excel: Used for getting basic idea how the dataset looks after directly downloaded from the site
2.Pandas: For EDA, cleaning, Merging,Visualizations and trends 
3.Matplotlib and Seaborn: For generating static Visualizations such as bar charts, box plots, and sctater plots
4.Plotly: For creating intractive maps and complex visualizations
5.Jupyter Notebook: Used for documenting the analysis and presenting results
6.Numpy: For numerical calculations and statistical analysis
7.Tableau: For creating interactive dashboard
8.PowerPoint: For introduction of Project
9.Git: For version control and collaboration

# Data Sources:This project uses data from Our World in Data(https://ourworldindata.org/) and other datasets from Kaggle(https://www.kaggle.com/) that includes information on various helath indicators

Specific datasets are:
Obeisty prevalence by country
Gdp per capita by country
Daily protein intake per person
Daily calorie intake by person
Population by country
Daily steps 
Life expectancy by country
Monthly income
Meat consumption
These datasets were collected over multiple years, allowing for longitudinal analysis from 1990 to 2016.

# Conclusion
This analysis provides valuable insights and the distribution of Obesity prevalence varies across countries with some countries had the greatest increase in obesity rates over time, and none of the countries had a decrease in Obesity rates over time. There are countries with lowest Obesity rates in overall. The countries had higher 
Obesity rates in 2015 than compared to 1990. since the Obesity rates are increasing over time. Considering Gdp per capita, daily protein supply, life expectancy, daily calories suplly, population over time and monthly income, the  higher income coutries tend to have more Obesity rates, there is moderate correlation between Monthly income and Obesity prevalence, the people in wealthier countries have more access to processed foods and sedentary lifestyles.The correlation between Average steps taken and obesity prevalence is surprisingly very weak, the physical activity alone may not be a predictor of Obesity. 


