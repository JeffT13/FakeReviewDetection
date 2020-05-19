# FakeReviewDetection

# Using DL Techniques to classify real and fake reviews


## Embeddings
    - NLP from Scratch, GLoVe, GoogleNews
    - Parameters:
        --> Max sequence length
        --> Number of words in vocabulary
    - Google & Custom embeddings saved    

## ConvNet
    - Yoon Kim CNN for Sentence Classification
    - Sensitivity Analysis of CNN for SC
    - Britz Blog & Github: http://www.wildml.com/2015/12/implementing-a-cnn-for-text-classification-in-tensorflow/ 
    - Christopher Masch github: https://github.com/cmasch/cnn-text-classification
    - Parameters:
        --> FILTER_SIZES,FEATURE_MAPS,DROPOUT_RATE, Batch Size, Epochs
    - Poor & Very slow (Cannot run with full parameters)
    - Need to Include Latent Features and Proper Parameters for true evaluation
 
## LSTM
    - https://github.com/nsinha280/lstm-on-Yelp-review-data/blob/master/lstm-final.ipynb
    - https://towardsdatascience.com/understanding-lstm-and-its-quick-implementation-in-keras-for-sentiment-analysis-af410fd85b47
    - attempt to solve for training limitations while still utilizing embedding



### Notes

- positive and negative reviews converted to Fake and Genuine reviews
    --> Goal: Identify Fakes (even at the expense of false positives)
- Cleaning:
    --> No stopwords & punctuation
    --> Tokenize & Pad (could add latent features?)
- Metrics:
    --> 'accuracy', Recall(), AUC(), FalseNegatives()
- Models:
    --> References & Intent
    --> Parameters
    --> Conclusion
