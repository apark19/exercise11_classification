# exercise11_classification
Resampling

Which model had the best balanced accuracy score?
Which model had the best recall score?
Which model had the best geometric mean score?

Over sampling accuracy score: 0.7269
Smote accuracy score: 0.7274
Cluster centroid accuracy score: 0.7115
Combination accuracy score: 0.5999

Over sampling recall score: 70 / (70 + 31) = 0.6931
Smote recall score: 70 / (70 + 31) = 0.6931
Cluster centroid recall score: 77 / (77 + 24) = 0.7857
Combination recall score: 86 / (86+15) = 0.8515

Over sampling geometric mean score: 0.73
Smote geometric mean score: 0.73
Cluster centroid geometric mean score: 0.71
Combination geometric mean score: 0.54


Ensemble 

Use the above to answer the following:
Which model had the best balanced accuracy score?
Which model had the best recall score?
Which model had the best geometric mean score?
What are the top three features?

random forest accuracy score: 0.7337
easy ensemble accuracy score: 0.9317

Recall = true positive / (true positive + false negative)
random forest recall score: 63 / (63+38) = 
0.6238

easy ensemble recall score: 93 / (93+8) = 0.9208

Random forest geometric mean score: 0.73
easy ensemble geometric mean score: 0.93

collection_recovery_fee, out_prncp_inv, total_pymnt_inv
