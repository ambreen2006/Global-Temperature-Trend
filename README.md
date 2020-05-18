# Global-Temperature-Trend
This is analysis for a blog project required in Udacity Data Scientist Nanodegree. It uses several datasets to analyze with respect to the global temperature anomaly.

CRISP-DM process followed is documented below

## Dataset

* Various datasets are obtained and sources are documented in the reference section.
* Each variable used is explained in the notebook `Global Temperature Trend.ipynb`

## Data preparation

* NaN values are removed where applicable
* Data is standardized using standard scaler

## Analysis and Modeling

* The output variable's timeline is visualized seperately as well as with explanatory variables
* LinearRegression model is created using `scikit` to infer coefficients
* Different correlation methods with p-values are considered to understand the variables.