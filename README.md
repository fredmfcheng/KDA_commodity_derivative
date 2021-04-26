## 1. "DCE_OLS_(20EMA).ipynb"

A key driver analysis of the trade price of iron ore derivative of Dalian Commodity Exchange, by studying the relationship of the derivative price between i) the performance of global financial market and ii) the indices/ indicators of the steel market.

Feature Engineering: 
- data is transformed into weekly level to reduce the noise from the daily level.
- Exponential Moving Average (EMA) is computed to transform the data as percent deviation from the EMA

Feature Selection:
- combining Hierarchical Clustering, Mutual Information Regression and Variance Inflation Factor to mitigate the issue of Multicollinearity and conduct variable selection

Model Building:
- Regression is trained with the selected features for finding out the relationship between the trade price and the selected features 
