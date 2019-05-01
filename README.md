# Boston-Housing-Random-Forest-and-Gradiant-Boosting-Assignment
This study uses data from the Boston Housing Study case as described in "Marketing Data Science: Modeling Techniques for Predictive Analytics with R and Python" (Miller 2015) to evaluate four regression modeling methodes, including Stochastic Gradient Descent, Lasso Regression, Random Forest, and Gradiant Boosting Regressor. An alternative version of Random forest and Gradiant Boosting Regressor with different hyperparameter settings are also included for comaprison purpose. These methods are evaluated within a 5-fold cross-validation design, using root mean-squared error (RMSE) as an index of prediction error.**

The results show that the performance of Random Forests and Gradient Boosting methods are highly impacted by their hyperparameter settings. They can either outperform or underperform SGD and Lasso, depending on the values assigned to hyperparameter(s). The better-performed Random Forest model and better_performed Gradient Boosting model are each applied to the full data set, with Gradient Boosting model reaches 1.0 perfect explained_variance score, outperforming Random Forest model. Therefore, Gradient Boosting method is the recommended method to use.**

Both Random Forest and Gradient Boosting methods indentified criminal as the most important feature in predicting house value. Age is recognized by both models as the second important explainatory variable in predicting house values.** 
