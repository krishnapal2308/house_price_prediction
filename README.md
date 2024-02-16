# House Price Prediction

### Problem Statement:
A US-based housing company named Surprise Housing aims to enter the Australian market. The company specializes in using data analytics to purchase properties below market value and sell them for a profit. To facilitate this expansion, the company has acquired a dataset containing information on house sales in Australia.

The objective is to develop a regression model utilizing regularization techniques to predict the actual value of potential properties. This predictive model will aid in decision-making processes regarding property investment.

### Objectives:
- Identify significant variables that influence house prices.
- Assess the predictive power of these variables in determining house prices.
- Determine the optimal regularization parameter (lambda) for Ridge and Lasso regression.

### Business Goals:
The developed model will provide insights into the relationship between independent variables and house prices. This information will guide management in devising effective investment strategies, focusing on areas with high potential returns. Additionally, the model will enhance understanding of pricing dynamics within the Australian housing market.

### Conclusion:
After conducting extensive analysis and regression modeling using regularization techniques, we have arrived at valuable insights regarding the factors influencing house prices in the Australian market. The top 10 features identified through Ridge and Lasso regression, along with their correlations, provide crucial information for Surprise Housing's investment decisions.

### Ridge Regression Analysis:

The top 10 features identified through Ridge regression and their respective correlations are as follows:

| No. | Features             | Correlation |
|-----|----------------------|-------------|
| 0   | GrLivArea            | 0.650290    |
| 1   | OverallQual          | 0.446275    |
| 2   | Age_When_Sold        | -0.395515   |
| 3   | TotalBsmtSF          | 0.392232    |
| 4   | OverallCond          | 0.326162    |
| 5   | BsmtUnfSF            | -0.185278   |
| 6   | KitchenQual_Fa       | -0.165063   |
| 7   | LotArea              | 0.163189    |
| 8   | Neighborhood_Crawfor | 0.153074    |
| 9   | KitchenQual_TA       | -0.119856   |

### Lasso Regression Analysis:

Similarly, the top 10 features identified through Lasso regression and their respective correlations are as follows:

| No. | Features             | Correlation |
|-----|----------------------|-------------|
| 0   | GrLivArea            | 0.733558    |
| 1   | OverallQual          | 0.470663    |
| 2   | Age_When_Sold        | -0.431418   |
| 3   | TotalBsmtSF          | 0.374320    |
| 4   | OverallCond          | 0.359483    |
| 5   | BsmtUnfSF            | -0.193782   |
| 6   | LotArea              | 0.155855    |
| 7   | KitchenQual_Fa       | -0.152967   |
| 8   | Neighborhood_Crawfor | 0.151531    |
| 9   | SaleCondition_Partial| 0.114796    |


### Insights:
Both Ridge and Lasso regression highlight the importance of features such as living area (GrLivArea), overall quality (OverallQual), and age of the property (Age_When_Sold) in predicting house prices.
Other significant features include the total basement area (TotalBsmtSF), overall condition (OverallCond), and various neighborhood and kitchen quality factors.
### Business Recommendations:
Based on these findings, Surprise Housing can make informed investment decisions by prioritizing properties with favorable attributes identified through the regression analysis. By focusing on areas with high correlations to house prices and leveraging these insights, the company can optimize its investment strategy and maximize returns in the Australian housing market.

In conclusion, the regression models and feature analysis presented in this project serve as valuable tools for Surprise Housing's market entry and investment decision-making process in the Australian real estate sector.


