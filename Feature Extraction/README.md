There are three types of feature selection: 

                   Wrapper methods (forward, backward, and stepwise selection), 
                   
                   Filter methods (ANOVA, Pearson correlation, variance thresholding), and 
                   
                   Embedded methods (Lasso, Ridge, Decision Tree). 
 
 
 
Feature Selection is the process where you automatically or manually select those features which contribute most to your prediction variable or output in which you are interested in. Having irrelevant features in your data can decrease the accuracy of the models and make your model learn based on irrelevant features.
A feature is an X variable in your dataset, most often defined by a column. 


Benefits of feature selection
The main benefit of feature selection is that it reduces overfitting. By removing extraneous data, it allows the model to focus only on the important features of the data, and not get hung up on features that don’t matter. Another benefit of removing irrelevant information is that it improves the accuracy of the model’s predictions. It also reduces the computation time involved to get the model. Finally, having a smaller number of features makes your model more interpretable and easy to understand. Overall, feature selection is key to being able to predict values with any amount of accuracy.


Overfitting occurs when a statistical model or machine learning algorithm captures the noise of the data. Intuitively, overfitting occurs when the model or the algorithm fits the data too well.  Specifically, overfitting occurs if the model or algorithm shows low bias but high variance.


Underfitting occurs when a statistical model or machine learning algorithm cannot capture the underlying trend of the data.  Intuitively, underfitting occurs when the model or the algorithm does not fit the data well enough.  Specifically, underfitting occurs if the model or algorithm shows low variance but high bias.  Underfitting is often a result of an excessively simple model.



Feature: an x variable, most often a column in a dataset.

Feature selection: optimizing a model by selecting a subset of the features to use.

Wrapper method: trying models with different subsets of features and picking the best combination.

Forward selection: adding features one by one to reach the optimal model.

Backward selection: removing features one by one to reach the optimal model.

Stepwise selection: hybrid of forward and backward selection.adding and removing features one by one to reach the optimal model.

Filter method: selecting a subset of features by a measure other than error (a measure that is inherent to the feature and not dependent on a model).

Pearson Correlation: a measure of the linear correlation between two variables.

Variance thresholding: selecting the features above a variance cutoff to preserve most of the information from the data.

ANOVA: (analysis of variance) a group of statistical estimation procedures and models that is used to observe differences in treatment (sample) means; can be used to tell when a feature is statistically significant to a model.

Interacting term: quantifies the relationship between two of the features when they depend on the value of the other; alleviates multicollinearity and can provide further insight into the data.

Multicollinearity: occurs when two or more independent variables are highly correlated with each other.

Embedded method: selecting and tuning the subset of features during the model creation process.

Ridge Regression: a modified least squares regression that penalizes features for having inflated beta coefficients by applying a lambda term to the cost function.

Lasso Regression: similar to ridge regression, but different in that the lambda term added to the cost function can force a beta coefficient to zero.

Decision Tree: a non-parametric model that using features as nodes to split samples to correctly classify an observation. In a random forest model, feature importance can be calculated using mean decrease gini score.

Cross Validation: a method to iteratively generate training and test datasets to estimate model performance on future unknown datasets.
