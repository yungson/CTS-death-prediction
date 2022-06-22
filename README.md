# CTS-death-prediction

This project employs xgboost to predict death risk using the California Teachers Study(CTS) data,  together with OSHPD hospitalization records.  The main objective of this project is to predict the short-term risk of death based on prior in-patient hospitalization, counting for subject-specific factors such as baseline characteristics from the CTS questionnaires 1-3(e.g. race, ethnicity,height, co-morbidties). We will develop the best fitting model through machine learning xgboost method to predict the probability of death within 60 days.

[see the full report here](https://yungson.github.io/CTS-death-prediction/cts-death-prediction.html)

## Results

|metrics| xgboost_default_paras | xgboost_random_parameter_tuning | xgboost_using_WOE |
| :---------- | ----------: | ----------: | ----------: |
| Accuracy  | 0.8932374 | 0.8906883 | 0.8954866 |
| Precision | 0.8377595 | 0.8357629 | 0.8469039 |
| Recall    | 0.8218854 | 0.8147797 | 0.8193396 |
| F1        | 0.8297465 | 0.8251379 | 0.8328938 |
