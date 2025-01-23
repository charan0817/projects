1.Classification Models
Two classification models were developed:
  i.Stepwise Regression Model:
    R-squared: 0.6192
    Adjusted R-squared: 0.5983
    Key predictors: RPG, PPG interactions, APG squared
  ii.Random Forest Model:
    Mean Squared Residuals: 2.637338e+13
    Variance explained: 53.94%
    R-squared: 0.9048
  The Random Forest model outperformed the Stepwise Regression model in terms of predictive accuracy and consistency.

2.Model Evaluation
A threshold of $351,983 (median salary) was set to classify salaries as high or low. The Random Forest model was evaluated using various metrics:
Precision: 0.80
Recall: 0.99
ROC curve: Showed strong model performance with a curve close to the top-left corner The model excelled at identifying high-salary players but occasionally misclassified lower salary players as high salary.

3.Conclusion
This project demonstrated the effectiveness of machine learning techniques in predicting NBA player salaries based on performance metrics. The Random Forest model showed superior performance, explaining about 90% of the variance in salaries. The analysis highlighted the importance of scoring, rebounding, and playing time in determining a player’s market value. Future refinements could focus on reducing false positives in high salary predictions to improve overall model accuracy.
