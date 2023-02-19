# Data-science-project-of-Recipes-and-Ratings
Data analysis on the Recipes and Ratings. 

### Introduction 




### Cleaning and EDA
#### Data Cleaning



#### Univariate Analysis
<iframe src="assets/rating histogram.html" width=800 height=600 frameBorder=0></iframe>

#### Bivariate Analysis

Scatter plot between rating and calories
The scatter plot shows how the amount of calories are distributed across the ratings 

print(data.groupby('rating')['calories'].agg(['mean','count']).to_markdown)









#### Interesting Aggregates










### Assessment of Missingness
#### NMAR Analysis



#### Missingness Dependency


### Hypothesis Testing

#### Hypothesis Testing
