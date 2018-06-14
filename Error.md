If you are getting an error while applying feature scaling:
'x must be numeric'
Then, apply feature scaling to only those columns which is not factorized during categorical variable encoding
Because factor function in R does not convert categorical variable into numerical values
