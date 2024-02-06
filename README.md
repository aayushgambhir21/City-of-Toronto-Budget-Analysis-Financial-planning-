# City of Toronto Budget Analysis (Financial planning)

## Description of the Project 

This project aims to analyze comprehensive budgeting data for programs within the City of Toronto, sourced from official government channels and municipal websites. The dataset includes essential details such as program names, detailed expenditure and revenue categories, and corresponding budget amounts. Our goal is to provide valuable insights that will inform financial planning and decision-making processes for the City of Toronto.

The analysis plan consists of several components:
1. Exploratory Data Analysis (EDA): Conduct basic statistical analysis and visualize budget allocations to understand the characteristics of the data.
2. Expenditure and Revenue Category Analysis: Categorize expenditures, explore their distribution across categories, and conduct subcategory analysis.
3. Program Summary: Aggregate expenditures by program, identify programs with the highest and lowest budgets, and visualize budget distributions.
4. Trend Analysis: Analyze budget trends over multiple years, identifying significant changes in allocations over time.
5. Predictive Modeling: Explore the possibility of building predictive models to forecast future budget allocations.
6. Comparison with Demographic Data: Investigate the relationship between budget allocations and demographic indicators.
7. Correlation Analysis: Examine potential correlations between budget categories to understand their interdependencies.

The project will address the following questions:
1. What insights can we derive from the averages of the operating budget data?
2. How have categories of expenses/revenues changed over time?
3. What do consistent expenditure trends and rankings across categories reveal about the city's financial priorities?
4. Does area demographics influence budget allocation?
5. What insights do outliers in Toronto's operating budget provide when analyzing expenses and revenues separately?
6. What trends are observed in revenue and expenses for different categories and programs over a five-year period?
7. What is the overall behavior of revenue over the past 10 years using a simple moving average?
8. Which category has the highest and lowest expenses for each year?
9. Are there any fluctuations in trends for specific categories in any year?
10. Which subcategory has the highest contribution in terms of expense and revenue?
11. What is the percentage contribution of each category for each year?
12. Is there any correlation between different revenue and expense categories?
13. How does the relationship between years and categories evolve over time?

## Datasets used: 
1. https://open.toronto.ca/dataset/budget-operating-budget-program-summary-by-expenditure-category/
2. https://open.toronto.ca/dataset/budget-capital-budget-plan-by-ward-10-yr-approved/
3. https://www12.statcan.gc.ca/census-recensement/2021/dp-pd/prof/details/download-telecharger.cfm?Lang=E&SearchText=toronto%20centre&DGUIDlist=2023A000435109&GENDERlist=1,2,3&STATISTIClist=1,4&HEADERlist=0 


## Analysis 
See analysis.docx for full analysis.


## Limitations
Regarding the demographic impact, the Federal Electoral District data for 2021 was sourced from Census Canada, which utilizes only a 25% sample data. Ward profiles from the City of Toronto are publicly available only up to 2016. Upon reaching out to the Social Policy Analysis & Research unit of the Social Development, Finance, and Administration division at the City of Toronto, it was mentioned that the 2021 profiles are currently being developed and will be released soon. They directed me to the data from Statistics Canada for the time being.

Additionally, there is a category exhibiting a negative value in the summary. This negative value indicates the presence of unaccounted expenses. These unidentified costs are likely included as adjustments to reconcile the total operating budget. This underscores the need for further investigation to categorize and understand these expenses, as they do not align with any specific category.
