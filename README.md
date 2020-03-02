# Concrete-strength-prediction

Data Description:
The actual concrete compressive strength (MPa) for a given mixture under a
specific age (days) was determined from laboratory. Data is in raw form (not
scaled).The data has 8 quantitative input variables, and 1 quantitative output
variable, and 1030 instances (observations)

Context:
Concrete is the most important material in civil engineering. The concrete
compressive strength is a highly nonlinear function of age and ingredients.
These ingredients include cement, blast furnace slag, fly ash, water,
superplasticizer, coarse aggregate, and fine aggregate.

Attribute Information:
1. Cement : measured in kg in a m3 mixture
2. Blast : measured in kg in a m3 mixture
3. Fly ash : measured in kg in a m3 mixture
4. Water : measured in kg in a m3 mixture
5. Superplasticizer : measured in kg in a m3 mixture
6. Coarse Aggregate : measured in kg in a m3 mixture
7. Fine Aggregate : measured in kg in a m3 mixture
8. Age : day (1~365)
9. Concrete compressive strength measured in MPa

Steps and tasks done:
1. Exploratory data quality report reflecting the following
a. Univariate analysis:
Univariate analysis – data types and description of the
independent attributes which should include (name,
meaning, range of values observed, central values (mean and
median), standard deviation and quartiles, analysis of the
body of distributions / tails, missing values, outliers
b. Multivariate analysis: 
Bi-variate analysis between the predictor variables and
between the predictor variables and target column. Comment
on your findings in terms of their relationship and degree of
relation if any. Presence of leverage points. Visualize the
analysis using boxplots and pair plots, histograms or density
curves. Select the most appropriate attributes
c. Strategies to address the different data challenges such as data
pollution, outliers and missing values
2. Feature Engineering techniques
a. Identify opportunities (if any) to create a composite feature, drop a
feature
b. Decide on complexity of the model, should it be simple linear
mode in terms of parameters or would a quadratic or higher degree
help
c. Explore for gaussians. If data is likely to be a mix of gaussians,
explore individual clusters and present your findings in terms of
the independent attributes and their suitability to predict strength
3. create the model 
a. Obtain feature importance for the individual features using
multiple methods and present your findings
4. Tuning the model
a. Algorithms that you think will be suitable for this project
b. Techniques employed to squeeze that extra performance out of the
model without making it overfit or underfit
c. Model performance range at 95% confidence level
