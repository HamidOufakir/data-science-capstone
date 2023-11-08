# IBM-Data-Science-Capstone-SpaceX
## Introduction
SpaceX, a leader in the space industry, strives to make space travel affordable for everyone. Its accomplishments include sending spacecraft to the international space station, launching a satellite constellation that provides internet access and sending manned missions to space. SpaceX can do this because the rocket launches are relatively inexpensive ($62 million per launch) due to its novel reuse of the first stage of its Falcon 9 rocket. Other providers, which are not able to reuse the first stage, cost upwards of $165 million each. By determining if the first stage will land, we can determine the price of the launch. To do this, we can use public data and machine learning models to predict whether SpaceX – or a competing company – can reuse the first stage.


![68747470733a2f2f63662d636f75727365732d646174612e73332e75732e636c6f75642d6f626a6563742d73746f726167652e617070646f6d61696e2e636c6f75642f49424d446576656c6f706572536b696c6c734e6574776f726b2d445330373031454e2d536b696c6](https://github.com/Hamidouf123/data-science-capstone/assets/96210728/13759061-5b44-4661-8dad-f1fc2932b678)

## Executive Summary

The research attempts to identify the factors for a successful rocket landing. To make this determination, the following methodologies where used:

* [Data collection:](https://github.com/Hamidouf123/data-science-capstone/blob/main/Collecting%20the%20data_API.ipynb) collect data using SpaceX REST API
* [Data collection:](https://github.com/Hamidouf123/data-science-capstone/blob/main/Collecting_webscraping.ipynb) collect data using web scraping
* [Data wrangling:](https://github.com/Hamidouf123/data-science-capstone/blob/main/Data%20wrangling.ipynb) replace null value and convert data no numeric to numeric 
* [Data Analysis:](https://github.com/Hamidouf123/data-science-capstone/blob/main/_Complete%20the%20EDA%20with%20SQL.ipynb) the data with SQL, calculating the following statistics: total payload, payload range for successful launches, and total # of successful and failed outcomes
* [Data visualization:](https://github.com/Hamidouf123/data-science-capstone/blob/main/EDA%20with%20Data%20Visualization.ipynb) the launch sites with the most success and successful payload ranges
* [Lunch sites location visualization](https://github.com/Hamidouf123/data-science-capstone/blob/main/Launch%20site%20location.ipynb) launch site success rates and proximity to geographical markers
* [Build Models:](https://github.com/Hamidouf123/data-science-capstone/blob/main/SpaceX_Machine%20Learning%20Prediction.ipynb) to predict landing outcomes using logistic regression, support vector machine (SVM), decision tree and K-nearest neighbor (KNN)
* [Create Dashboard:](https://github.com/Hamidouf123/data-science-capstone/blob/main/spacex_dash_app.py) Build an Interactive Dashboard with Ploty Dash.
