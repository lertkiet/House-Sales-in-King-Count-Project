# House Sales in King County Project

## Project Summary
This repository features a Python-based analysis of house sales in King County, Washington. To ensure a property is accurately priced, a thorough analysis should always be conducted before buying or selling. This project explores the housing market in King County, identifying the factors that influence home prices. 
Using machine learning models, it predicts accurate market values based on these factors, providing insights to support fair and informed pricing decisions.

## Geographical Overview
King County, the most populous county in Washington State, ranks as the 12th most populous county in the United States. It is home to Seattle, the state's largest city, with approximately two-thirds of the county's population residing in surrounding suburbs.

This case study examines the factors influencing housing prices in King County, WA. The analysis includes a geographical overview of the locations of houses within the dataset. By applying various analytical techniques, the study aims to uncover key insights into the primary drivers of housing prices across the county.

## Key Questions
The hypotheses based on the data gathered:

## Data Used for this Analysis
The dataset, sourced from Kaggle.com, consists of administrative data from over 21,000 house sales in King County, recorded between May 2014 and May 2015. This publicly available, open-source dataset serves as the foundation for the analysis.

1. An increase in square footage (sqft_living) will result in higher house prices.
2. Houses built after 1980 are more likely to have higher prices compared to older homes.
3. Two-story houses are generally associated with higher house prices.
4. Future house price trends are expected to remain stable, with a slight upward trajectory.
5. Significant differences across zip codes will lead to variations in house prices, with some neighborhoods exhibiting higher prices than others.

## Tools
1. Microsoft Excel
2. Python
3. Tableau

Click to see visualizations here: https://public.tableau.com/app/profile/lertkiet.lertchayantee/viz/KingCountyWAHouseSalesAnalysis/Presentation

## Conclusion and Recommendations
#### 1. Linear Regression:
Applying linear regression in machine learning helps identify significant relationships between variables in the dataset. From this method, we observed that increasing the number of square feet (sqft_living) generally leads to higher house prices. 

However, the regression output indicates that the relationship is not entirely linear. The data points scattered around the regression line suggest that other factors also influence house prices. Exploring additional techniques such as clustering analysis can provide deeper insights.

2. Clustering Analysis:
Clustering analysis allows us to uncover insights that may be overlooked with linear regression. This method treats all variables equally without introducing bias. By applying this machine learning algorithm, we identified three distinct groups of houses: luxurious, mid-range, and affordable.

3. Key Insights:
- Houses with the highest price per square foot are predominantly located in densely populated areas, such as Seattle and Bellevue.
- Square footage (sqft_living) has the strongest influence on house prices, while other factors, such as the number of bedrooms/bathrooms, property condition, and year built, have a relatively minor impact.

4. Next Steps:
- Update the Dataset: Collect recent home sales data to analyze price trends over time and validate current market insights.
- Incorporate Additional Features: Examine the impact of additional factors, such as proximity to amenities, school districts, and neighborhood crime rates, on house prices.


