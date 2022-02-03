# Overview
One of the most vital parts of comprehension of natural language processing is sentiment analysis. It is a popular method to summarize and analyze huge amounts of feedback and gain valuable insights.

Now more than ever, people’s opinion is based on other people’s opinion. The internet has become a trove of opinions. Major companies notice what people are saying about their brains online, in digital media, in order to do better than their competitors. The major requirement for big brands is to determine whether people are putting positive or negative feedback related to their brand. A major problem is that some ratings do provide a number but not context behind it.

# Long Short Term Memory LSTM
Previously linear models were used in representing the lexical features of the data set, which were the bag of words that is entirely based on the frequency of words and the bag of n-grams that improves the performance of the bag of words. Now we use LSTM, CNN, and RNN models in such cases. RNN is a very biased model this means that the previous words can weakly influence the decision of the latter that arrives. Thus, the LSTM layer is better since it represents each sentence and then passes an RNN variant of the network over them.
![image](https://user-images.githubusercontent.com/64677115/152351011-c497d8b2-4cc1-4b38-8fb5-806812f240dd.png)


# LSTM Based Attention Model
As explained in the above mathematical model LSTM was formulated for a better understanding and performance than the feed-forward neural network. The architecture of Attention-based LSTM. The aspect embeddings have been used to decide the attention weights along with the sentence representations.

Part of this concept is to train the model in an end-to-end pathway using backpropagation where the objective loss function is cross-entropy loss. We use such an Attention-based LSTM model, since it had the ability to consider the different parts of the sentence where different sentiments are concerned, showing effective results. In order to fulfill the limitation of a probability density, a softmax function is added that simply generalizes the logistic function so that all the logic sum up to 1.
![image](https://user-images.githubusercontent.com/64677115/152350921-903acc41-1233-4b06-9c49-15f12e1a5db9.png)
