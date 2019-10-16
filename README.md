# RNN Text Classification


Hi,


First, we'll pass in words to an embedding layer. We need an embedding layer because we have tens of thousands of words, so we'll need a more efficient representation for our input data than one-hot encoded vectors. 

However, it's good enough to just have an embedding layer and let the network learn a different embedding table on its own. In this case, the embedding layer is for dimensionality reduction, rather than for learning semantic representations.

After input words are passed to an embedding layer, the new embeddings will be passed to LSTM cells. The LSTM cells will add recurrent connections to the network and give us the ability to include information about the sequence of words in the movie review data.

Finally, the LSTM outputs will go to a LogSoftmax output layer. We're using a softmax function our target variable can have 5 classes, and a softmax will output labels, values between 0-4.

We can also do the above task with a CNN.

Rest details are documented with the code.

Thank you,
Akash Jain
