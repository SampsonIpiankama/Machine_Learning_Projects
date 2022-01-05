# House Price Prediction

The oject of the project was to predict housing prices based on its features using ordinary least squares (OLS) linear regression model. 

# Libraries
1. Numpy
2. Pandas 
3. Matplotlib
4. Seaborn 
5. re (Regular expression)
6. Scikit Learn

# Steps involved
1. I imported the necessary libraries.
2. I imported the dataset and carried exploratory analysis.
3. I visualized the data (heatmap chart and distribution plot).
4. I used Label Encoder to convert columns with categorical data into numerical data.
5. I carried out feature selection and data splitting.
6. I used feature scaling to transform the data so that it fits within a specific scale of 0 - 1.
7. I carried out modeling using OLS linear regression model.
8. I evaluated the model using the ‘r2_score metric.

# Data Visulaization
In this step I am going to produce two types of charts.
1. Heatmap
2. Distribution Plot

![Heatmap](https://user-images.githubusercontent.com/92667306/148219729-93a148d6-7782-4276-8451-9e92a766267b.png)

# Conclusion
The R-squared of the OLS linear regression model is just a abit above 60% which is poor. Therefore, that the OLS linear regression model is not a strong predictor and is not suitable to for our house price dataset.

# Recommendation
Other regression models like the, Lasso, Ridge, Bayesian, and Elastic Net should be tested so know which is of them is highest predictor of the housing price.
