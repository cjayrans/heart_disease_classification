# Heart Disease Classification

### Overview
Showcase different feature selection methods for a binomial classification problem using both logistic regression and forward learning tree-based models in Python.

### Feature Selection Methods
- Backward Elimination
- ANOVA
- Recursive Feature Elimination
- Select From Model

### Classification Models
- Logistic Regression
- Gradient Boosted Machines (h2o)

### Conclusion
Each of the feature selection methods resulted in similar outcomes for selected predictor variables. These methods should be used as a starting point, but should ultimately be validated during simulation testing. 

Since the Heart Disease example from Kaggle contains such as small sample set (300 records), more complex methods such as GBMs do not have the same advantage as they typically do with larger data sets. Even when applying cross-validation with a hyper parameter grid search, the logistic regression and GBM models performed about the same with respect to precision, recall, and F1 score. 
