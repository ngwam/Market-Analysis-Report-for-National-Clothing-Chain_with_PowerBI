# Market-Analysis-Report-for-National-Clothing-Chain_with_PowerBI
 In this project, you will use population statistics from the US Census Bureau to determine where the greatest income exists around the country and whether there is a correlation between sales and income. We don’t know the incomes of our customers, but we should be able to predict it by looking at their purchase history and locations and comparing that against the census data. Additionally, we want to analyze our inventory, specifically customer ratings and return rate and see if there’s a correlation between the two.

# Project Instructions

## Project Scope

In this project, analyze US Census Bureau statistics to identify regions with the highest income and explore the correlation between sales and income. Predict customer income using purchase history and locations. Additionally, investigate inventory by analyzing customer ratings and return rates for potential correlations.

## Draw Conclusions

### Analysis Questions

1. What is the correlation (R2 value) between sales and income?
2. What is the correlation (R2 value) between customer ratings and product return rate?
3. What are the linear regression formulas to predict customer income from customer sales?
4. Which customer is predicted to have the highest income?
5. Which product will be advertised the most?

## Present Your Analysis

Present your analysis as a 1-page written summary and visual report in Power BI. Utilize the following visuals:

1. **Income Distribution:** Histogram
2. **Household Income by Location:** Map
3. **Correlations:** Scatter Plot with Trendline and Card with R^2 value

Use additional visuals as needed to convey the results effectively.

## Histogram

Determine histogram parameters for your project. Consider the histogram's purpose – to provide insight into data distribution. Ensure your histogram(s) convey important statistics. Utilize a column chart for flexibility in defining ranges and columns using DAX formulas.

![Example Histogram](https://video.udacity-data.com/topher/2021/February/603afaf5_histogram/histogram.jpg)

# Analysis Interpretation

## 1. Correlation between Sales and Income

The correlation (R2 value) between sales and income is 0.78, indicating a strong positive correlation. An increase in average income by state correlates with an increase in the average sales over the last 6 months.

## 2. Correlation between Customer Ratings and Product Return Rate

The correlation (R2 value) between customer ratings and product return rate is 0.88, suggesting a strong negative correlation. Higher customer ratings lead to a decrease in the return rate of products.

## 3. Regression Formulas for Predicting Customer Income

The regression formula is Y = 0.01x - 722.17, where 0.01 is the gradient (slope) of the linear regression, and -722.17 is the intercept.

## 4. Customer with the Highest Income

The customer predicted to have the highest income is from District Columbia.

## 5. Most Advertised Product

The product "Leader Back" is expected to be advertised the most due to its competitive pricing standards compared to other products, generating a higher demand for advertising.

**Conclusion:**
- Niche customers with an income range of $70,000–$80,000 are identified as the most frequent customers. Notably, these niche customers are primarily from Maryland, as revealed by the heatmap. The analysis indicates a low return rate for products when customer ratings are high, emphasizing the strong correlation between the two.

**Proposals for Further Analysis:**
- The current study has limitations, such as not exploring all correlations and distributions in the dataset. Future analyses should comprehensively study all aspects of the dataset to recommend specific products in specific areas. This will provide a more nuanced and comprehensive understanding for informed decision-making.
