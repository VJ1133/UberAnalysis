# UberAnalysis

Objective:

The goal is to discover any concealed or undiscovered insights in the dataset by conducting exploratory data analysis. We aim to understand how each field in the dataset relates to the price by examining their effects on each other. We will use various machine learning models to analyze the data. Next, we will compare and analyze the outcomes of these machine learning models based on their accuracy, and then recommend the most effective model for future price predictions.

Performed EDA to gain insights into the data and visualized it using various plots. This revealed that the dataset lacked information on taxi prices and featured price variations of other cabs and weather conditions. Then converted categorical values to continuous data and filled missing values using the median of other values. The most crucial step was feature selection, which I accomplished using recursive feature elimination, leading to the selection of the top 25 features.Dropped some of these features and ended up with 8 essential columns.Then applied four different models to the remaining dataset, with Decision Tree, Random Forest, and Gradient Boosting Regressor performing exceptionally well with over 96% accuracy on training. Ultimately chose Random Forest as it was less likely to overfit and built a function using the same model to predict prices.

Dataset: https://www.kaggle.com/datasets/brllrb/uber-and-lyft-dataset-boston-ma


