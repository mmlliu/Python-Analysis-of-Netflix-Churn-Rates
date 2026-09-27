# Python-Analysis-of-Netflix-Churn-Rates
This study uses python to answer the question: to what extent are average daily watch times and monthly fees associated with Netflix customer churn, and which variable has the stronger association?

## Tools
**Language:** Python

**Platform:** Jupyter Notebook (in Visual Studio Code)

**Database:** https://www.kaggle.com/datasets/zeyadmohamed26/netflix-customer-churn-and-engagement-analytics/data

## Methods
- Exploratory data analysis
- Box plots
- Chi-square tests
- Cramér's V
- Welch's t-tests
- Point-biserial correlations

## Key Findings
Average daily watch time showed a substantially stronger
association with customer churn than monthly fee.

- Watch time: r = -0.365, p < 0.001
- Monthly fee: r = -0.153, p < 0.001
- Watch-time Cramér's V = 0.744
- Monthly-fee Cramér's V = 0.163

## Conclusion
Both average daily watch time and monthly fees have a statistically significant association with churn rate. However, the analysis indicates that watch time has a stronger association and those with low daily watch times were considerably more likely to churn. Though low monthly fees is associated with a higher likelihood to churn as well, the association was considerably weaker.

## Limitations
For starters, because correlation != causation, it cannot be said that low watch times /cause/ churn. Then, there was an unusually strong relationship between watch times and churn, which may bring into question the legitimacy of the data set, which might not actually be reflective of all Netflix customers because of other demographic factors.




