# Tech-Question-Tag-Prediction


Using the data from [Stack Overflow questions](https://www.kaggle.com/stackoverflow/stacksample), I Have created a DL model that predicts the associated tag based on the question.


Following are the steps followed:

- Cleaning of the data
   - Combining tags 
   - Removing duplicates
   - Selecting top 100 tags

- Processing of the text columns
    - Removing contractions & Punctuations
    - Lemmatizing tokens
    - Removing stop-words

- Running of Keras model
    - Feature engineering of data
        - Embeding and padding data
        - Creating feature and target matrix
    - Loss function plotting

- Improving the model
    - Extra tag using least frequent terms



