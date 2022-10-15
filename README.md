# Churn-Prediction-in-Telecom
Churn-Prediction-of-Telecom-Data
This project is focused on end to end application of Machine Learning methodologies to achieve best predicting accuracy. Our goal is to predict churn rate of customers for a telecom service provider based on service charges and usage data of customer.

The dataset which will be used for this project is Telecom data which comprises of 6999 entries and 21 columns which describe the various factors that affect churn and churn column would be my target variable. It is available in Kaggle. 21 columns of dataset are, State, account length, area code, phone number, international plan, voice mail plan, number of voicemail messages, total day minutes, total day calls, day charge, evening minutes, eve calls, evening charge, night minutes, night charge, international minutes, international calls, international charge, customer service calls, churn etc.

SOURCE: https://www.kaggle.com/becksddf/churn-in-telecoms-dataset

Our goal is to predict customers who are most likely to churn or change telecom networks. As it turns out to be a classification problem, I am using Logistic Regression from regression algorithms, K-Nearest Neighbors to learn how Nearest-Neighbors would work on this dataset and Random forest algorithms from decision trees family to perform classification analysis on data to predict churn.

To overcome the problem of overfitting I have applied PCA and also clustered the categorical columns to avoid information loss from those columns.

To improve the model and to perform hyper parameter tuning, I have successfully applied Ensemble method (Bagging) and Grid Search. From my analysis, I have observed that Random Forest Classifier is best model fit to the data set being an ensemble method it gave better results. Though I have applied Bagging, Grid Search, the accuracy has increased only by 2% even after lot of hard work.

But after performing Random Forest on data which is Clustered and applied PCA gives an accuray of 97% on test data which is 2% more than just Random Forest classifier.

# Conclusion:
Customers in the telecommunications business have access to several service providers and may actively move from one operator to another. In this highly competitive sector, the typical yearly turnover rate for the telecoms industry is between 15 and 25 percent.
Given that it costs five to ten times as much to gain a new client as it does to maintain an existing one, customer retention has surpassed customer acquisition in importance.
In order to control High Value Customer Churn, we have identified the customers most likely to churn and the variables that contribute to the high churn rate.
The exploratory research revealed a significant decline in recharge, call use, and data consumption during the 'Action Phase' in the eighth month. From the list of significant predictors of churn, the following is once again evident:

'arpu_7',
'max_rech_amt_6',
'std_og_t2m_mou_8',
'loc_og_t2m_mou_8',
'max_rech_data_8',
'last_day_rch_amt_8',
'total_data_rech_8',
'total_amt_8',
'roam_og_mou_8',
'loc_ic_t2m_mou_8'
The'seventh month' average revenue per user plays a crucial part in determining churn. A rapid decline in it may suggest that the client is considering churning, prompting the need for immediate action.

Local & STD Minutes of use (incoming & outgoing) have the greatest impact on client retention.
Lastday of recharge amount in the action phase is also a significant factor in determining churn.
The maximum rcharge for calling data by a customer in the sixth month and eighth month should be carefully targeted, since the sixth month represents the beginning of the good phase and the eighth month represents the action period.
Indicators of churn include the last day of recharging in the eighth month, the total quantity of data recharged in the eighth month, and the total amount customers spend on calls and data in the eighth month.
Roaming calls made by customers during the eighth month also play a crucial part in determining attrition.
Following strategies can be incorporated :

Sudden decrease in Local & STD Minutes of consumption may be the result of inadequate customer service, a subpar network, or inappropriate customer schemes/plans. Efforts must be made to provide a superior network and prioritize customer happiness.
Such consumers should be offered with customized strategies to prevent churn.
Routine feedback calls might be made to customers based on their consumption or most recent recharge in order to understand their complaints and expectations. Suitable measures must be implemented to prevent their churning.
During the action phase, it is possible to entice clients by displaying a quick decline in the total amount spent on calls and data recharge.
Promotional offers are also beneficial
