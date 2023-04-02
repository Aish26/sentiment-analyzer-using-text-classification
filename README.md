## sentiment-analyzer-using-text-classification

### Introduction:
This project is aimed at performing sentiment analysis on movie reviews. It classifies the reviews into positive and negative sentiments. There are two techniques used here.
- A word2vec model
- A Long Short Term Memory model
The similarity of words obtained by both models are analyzed and visualized using a plot.

### Business value:
With a large number of reviews received by an online business, it is almost impossible to go through each one of them to understand the customer sentiment. These reviews not only represent the overall impact on the user but also highlights the improvement opportunities. Instead of guessing the improvements to improve revenue, its any day better to get an idea of concrete issues from the users. It is also recommended to work on existing issues first before getting into developing new features.

The sentiment analyzer developed in this project would help ingest large amount of reviews by classifying them into positive and negative reviews. This way the quantity of happy and unhappy users can be compared. It also filters the negative reviews so these will be the only ones that needs further analysis and contains the hints for further business improvement.

### Concepts:
- word2vec: It is a natural language processing model that uses a corpus of text to learn association of words. Each word is represented by a vector which captures the semantics and qualities of that word. The similarity between words is gauged by the distance between these vectors in vector space. The closer the vectors, the similar the words in meaning/context.
The technique picks words falling in the mentioned window. For eg. in a window of size 5, 5 words before and 5 words after would be picked from the text. The frequency of words falling in the same window relates to their similarity in context.

- LSTM: It is a recurrent neural network model that has a capability to learn long term dependencies. A neural network is a combination of multiple logistic regression functions. An RNN learns the context and meaning of the word and creates embeddings. These embeddings are representation of word tokens.
Here the classification has been done using already trained gensim embeddings as well as embeddings obtained by training an LSTM model.

- Principal component analysis: It is a technique to reduce dimensionality of data by rotating dimensions in the direction with most variation. It is applied on the high dimensional data so the dimensions that explain the most variation can be used for prediction. PCA also helps in resolving for overfitting.

### Tools and Technologies Used: 
- Python
- Google Colab
- Tensorflow
- Long Short Term Memory
- word2vec
- Principal Component Analysis



