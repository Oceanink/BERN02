# Description
This notebook uses MLE to estimate the parameters of a GLM(Generalized Linear Model) with Poisson distribution. 
# Data
The data used is 'bird_count.csv' which contains the number of birds counted in different years.
# Model
The model uses 'yr' as predictor variable and 'count' as response variable. By minimizing the negative log likelihood, we can get the parameters of the model.
# Generate samples
Using the estimated parameters, we generate 'count' samples for each year 3 times and save them to 'samples.csv'.
