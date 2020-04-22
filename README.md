# FakeReviewDetection
Project for DS-GA 1003 Machine Learning. Identifying Fake Reviews using Yelp training data. Scoring and submission through Codalab

## Experiments
### Multinomial Naive Bayes 
 - Setup: only using reviews as input. Using Bag of word as the feature.
 - Result:
               ||precision|    recall|  f1-score |  support|
               |:-: |:-: |:-: |:-: |:-: |

           |0|       0.90 |     1.00  |    0.95 |    32270|
           |1|       0.75 |     0.00  |    0.01 |     3648|

 | macro avg    |   0.82    |  0.50  |    0.48 |    35918|
|weighted avg    |   0.88    |  0.90  |    0.85 |    35918|
It seems to be a strong baseline.
