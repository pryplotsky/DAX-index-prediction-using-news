# DAX Index Prediction Using News
We investigate how news articles and headlines influence the DAX stock market index. Our approach involves developing a model that takes business articles from major German newspapers, such as Die Zeit and Der Spiegel, as input and predicts whether the index will rise or fall the following day (a binary classification task).

Sentiment analysis of the news content and headlines is performed using a German-language version of BERT, a pre-trained transformer model developed by Google for Natural Language Processing (NLP). Each article is converted into a 768-dimensional feature vector using BERT.

These feature vectors are then used as inputs to a Long Short-Term Memory (LSTM) model, which captures temporal dependencies and predicts the direction of the DAX index movement on the following day.
