# credit-risk-classification

Pull and pushing from VS terminal not working, trying to solve issues but may have to resort to manually adding the file once completed.Completed on the 17/5 (had to manually import file).

Report:

1. An Overview of the Analysis:
- Purpose of the analysis is use classification to draw categorical conclusions about data. It determines whether loan applicants are creditworthy (no risk) or credit risks (high risk).


2. The results
  1. Machine Learning Model 1: Logistic Regression Model 
0 75036 , 1 2500
- Balanced accuracy score 0.9520479254722232
- The model accurately predicts low risk loans, with precision, recall (.99), and an f1-score of 1.00.
- F1 score moderately predicts high risk loans, with precision (0.85), recall (0.91) and an f1-score of .88. This is is slighly concerning as the model will corrrectly predict the high risk loan 85% of the time. and will misclassify them as low risk ~15% of the time.
  2. Machine Learning Model 2: Logistic Regression Model with resampled training data
1 56271, 0 56271
- Balanced accuracy score 0.9936781215845847
- The model accurately predicts low risk loans, with precision of 1, recall (.99), and an f1-score of 1.00.
- The model accurately predicts high risk loans, with precision of (0.84), recall (.99), and an f1-score of 0.91. It is a much more accurate at prediciting high risk loans. And there are only 0.09 high risk loans classified as low risks.
3. A summary
