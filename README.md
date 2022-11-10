# Ensemble-Model-Comparison
Comparing Bagging, Adaboost, Random Forest and XGBoost Ensemble.

The comparison of confusion matrices and calculations of accuracy scores indicate that there is severely decreasing returns upon the increase of estimators used in these models. For bagging there was a considerable improvement from 25 to 100 estimators reaching 86.4% accuracy, which fell off at 200 estimators back down to 85%. For Adaboost 50 estimators is what is best, but it is also only a .4% increase from 25 estimators. For Random Forest 50 maximizes the return more efficiently than 200 estimators, meaning that 50 trees is the best parameter for the effort, where as quadrupling that only increases the accuracy by 0.4%. XGBoost had the best performance of all the models, going beyond 99% accuracy.

When working with these types of ensemble models, the accuracy improvement at the deficit of higher complexity isn’t always beneficial, especially as it is likely to lead to over fitting, which jeopardizes deployment performance.
