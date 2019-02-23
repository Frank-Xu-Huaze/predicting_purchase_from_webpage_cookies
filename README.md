# predicting_purchase_from_webpage_cookies
This is a repo for a data project of predicting purchase from users' webpage cookies data. I used logistic regression, decision tree, random forest and gradient boosting to try to fit and make predictions.

Field Descriptions:

isbuyer - Past purchaser of product
buy_freq - How many times purchased in the past
visit_freq - How many times visited website in the past
buy_interval - Average time between purchases
sv_interval - Average time between website visits
expected_time_buy - ?
expected_time_visit - ?
last_buy - Days since last purchase.
last_visit - Days since last website visit.
multiple_buy - ?
multiple_visit - ?
uniq_url - Number of unique urls we observed web browser on.
num_checkins - Number of times we observed web browser.
y_buy - Outcome variable of interest, Did they purchase in period of interest.

Question: 

Each observation in the provided training/test dataset is a web browser (or cookie) in our observed Universe. The goal is to model the behavior of a future purchase and classify cookies into those that will purchase in the future and those that will not. y_buy is the outcome variable that represents if a cookie made a purchase in the period of interest. All of the rest of the columns in the data set were recorded prior to this purchase and may be used to predict purchase. 

Please use ‘ads_train.csv’ as training data to create at least two different classes of models (e.g. logistic regression, random forest, etc.) to classify these cookies into future buyers or not. Explain your choice of model, how you did model selection, how you validated the quality of the model, and which variables are most informative of purchase. Also, comment on any general trends or anomalies in the data you can identify as well as propose a meaning for those fields not defined. 

The deliverable is a document with text and figures illustrating your thought process, how you began to explore the data, and a comparison of the models that you created. When evaluating your models, consider metrics such as AUC of Precision-Recall Curve, precision, recall. This should take about 6 hours and can be done using any programming language or statistical package (R or Python are preferred). Finally, perform prediction on test dataset ‘ads_test.csv’ using your chosen model(s) and report predicted probabilities of future purchase and predicted labels of future purchase. 

