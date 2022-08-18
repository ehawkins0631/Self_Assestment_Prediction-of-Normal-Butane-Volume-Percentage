**Self_Assestment_Prediction-of-Normal-Butane-Volume-Percentage**

1.- Self Assestment:

- With our project we wanted to explain:
    * How a machine learning algorithm is used in data analytics.
    * Create training and test groups from Normal-Butane-Volume-Percentage data set.
    * Implement the logistic regression, decision tree, random forest, and Support Vector Machine algorithms.
    * Interpret the results of the logistic regression, decision tree, random forest, and support vector machine algorithms.
    * Compare the advantages and disadvantages of each supervised learning algorithm.
    * Determine which Supervised Learning algorithm is best used for Normal-Butane-Volume-Percentage data set.
    * Use ensemble and resampling techniques to improve model performance.

- ETL
We were able to create a function to extract, transform and load the three datasets. All three datasets were extracted into DataFrames correctly. The DataFrames were displayed and contained the correct columns. We cleaned Normal-Butane-Volume-Percentage data. We filtered out the Normal-Butane-Volume-Percentage, used try-except to drop duplicates. We list comprehension was used to drop columns with null values. The box values were converted correctly into strings. The budget, release date and running time were cleaned properly. Well done! On deliverable 3, the Kaggle data cleaning was tackled. Kaggle data was merged with data to form the Prediction-of-Normal-Butane-Volume-Percentage DataFrame. Unnecessary columns were dropped from this DataFrame, columns were renamed and missing Kaggle data was filled using Prediction-of-Normal-Butane-Volume-Percentage data. Normal-Butane-Volume-Percentage data was  cleaned and merged with the  Prediction-of-Normal-Butane-Volume-Percentage DataFrame. The empty rows were filled with zero. The DataFrames are displayed and have the correct columns.

- Web with HTML/CSS
All of prediction-of-Normal-Butane-Volume-Percentage images, tables, code were correctly displayed, stored, and retrieved. The data is properly displayed using HTML and aesthetically enhanced through CSS and additional bootstrap 3 components. 

- Pandas:
We were able to cohesively present a written analysis that summarizes the data displayed in the dataframe and multiple-line chart. We also explained the implication of both analyses.  We created our DataFrames in our notebook. It cont ained all the prediction-of-Normal-Butane-Volume-Percentage. The notebook also generated a summary DataFrame with all the requirements. We were effectively able to demonstrate the graph with annotations, x-axis is by dates and the correct graph style is used. We comprehensive reports and how you used the data to support it.

- Feature Importances
We also went ahead and calculated some feature importances, feature coefficients, and correlations to understand the relationships of the features among each other and with different model types. The feature importance functions such as model.coef_ and model.feature_importances_, along with naitive process knowlege of team group members, allowed for a systematic ranking of features. Though 54 of the original 56 features were left in the model, the feature importance ranking is a valuable output and will be used to further tune the model outside of the class project end date.

* Group Assestment

We cohesively present our analysis and draw reasonable conclusion from our Normal-Butane-Volume-Percentage data set:

In conclusion, there is certainly limitations to the model. While it does not predict the N-Butane Vol% exactly, it does seem to trend the general direction of the N-Butane Vol%, and generally predicts this figure within 2-5 Vol% points. By only allowing the prediction to occur when all input data streams are within normal operating conditions, performance is likly to improve.


* Summary of Project
Project Summary: Analysis Output Performance
Performance Metrics
The following performace metric results were gathered based on the X_test predictions.

Residual Plot: The plot in Figure 2 show evenly distributed residuals, thus giving reason to believe the model performs well and is not over-fit.
Figure 3: Residual Plot

![image](https://user-images.githubusercontent.com/101227930/185297754-189facfe-7a53-4692-80d8-6e8cbfc9ea06.png)


The total Mean Absolute Error is 1.92, meaning the average error is only 1.92 Vol%.
The total Root Mean Squared Error is 3.51
Absolute Deviation Accuracy: 84.3%
Total Deviation Accuracy: 99.4%

Real Time Model Performance
Finally, real time data, not included in the original dataset was taken from the past 3 weeks and ran in place of the X_test data as X_realtime data. Unfortunately, unit downtime during this time-span allowed only 4 days of continuous runtime data to be input. This real time data was input to the model to simulate an operators view of actual and simulated N-Butane Vol% in TA's recycle line. The results are shown in Figure 4 below.

Figure 4: Real Time Model Performance

Conclusion
In conclusion, there is certainly limitations to the model. While it does not predict the N-Butane Vol% exactly, it does seem to trend the general direction of the N-Butane Vol%, and generally predicts this figure within 2-5 Vol% points. By only allowing the prediction to occur when all input data streams are within normal operating conditions, performance is likly to improve.

![image](https://user-images.githubusercontent.com/101227930/185296714-bcfd6502-d606-4bbb-b380-967d5297828d.png)

Linear Regression.

![image](https://user-images.githubusercontent.com/101227930/185296822-b6f22c85-e3ec-47d9-8011-4a608a270f5d.png)


