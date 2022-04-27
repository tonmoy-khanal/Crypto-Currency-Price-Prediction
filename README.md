# Crypto-Currency-Price-Prediction
Cryptocurrency Price Prediction Using LSTM neural network
![crypto](https://user-images.githubusercontent.com/38865308/165442417-c0165348-06d0-4be0-bcd0-35c1c9642198.png)
The above Graph shows the Prediction of Price of Crypto Currency till 01-May-2022

# How this works?
Predicting crypto prices, stock prices, weather etc are all examlpes of time series forecasting. The idea is the future prediction depends on past information. RNN's and LSTM's have proved to be state of the art for these kinds of predictions. Due to this property i.e predicting on basis of previous context have made them favourite candidates for tasks like machine translation and language modelling. In fact Google Translate works on a much advanced and complex model of LSTM!

# What is LSTM?
LSTM's are sophisticated RNN units.

# What is RNN!?
Humans don’t start their thinking from scratch every second. As you read this essay, you understand each word based on your understanding of previous words. You don’t throw everything away and start thinking from scratch again. Your thoughts have persistence.

Traditional neural networks can’t do this, and it seems like a major shortcoming. For example, imagine you want to classify what kind of event is happening at every point in a movie. It’s unclear how a traditional neural network could use its reasoning about previous events in the film to inform later ones.

Recurrent neural networks address this issue. They are networks with loops in them, allowing information to persist.
![687474703a2f2f636f6c61682e6769746875622e696f2f706f7374732f323031352d30382d556e6465727374616e64696e672d4c53544d732f696d672f524e4e2d756e726f6c6c65642e706e67](https://user-images.githubusercontent.com/38865308/165443512-00bb4c2c-767a-466e-8406-07f987ef7fed.png)


# Recurrent Neural Network
While RNN may seem to be a good candidate for this task...unfortuanately it's not. RNN's, while they are good at storing short term dependencies, they are disaster when you need to keep track of longer dependencies due to vanishing gradient problem.

# LSTM to the rescue!
LSTM's are capable of stroring longer dependencies as it can decide on which information it should retain and which information it can throw away. A LSTM cell looks like this:
![687474703a2f2f636f6c61682e6769746875622e696f2f706f7374732f323031352d30382d556e6465727374616e64696e672d4c53544d732f696d672f4c53544d332d7661722d4752552e706e67](https://user-images.githubusercontent.com/38865308/165443447-bf4cdd24-49e2-4cc8-aaea-be1c3bf668f0.png)

# LSTM
These cells are really powerful in capturing context from long sequences hence is the state of the art.

So now we have a very basic model to predict not just crypto prices but any time sequence such as weather, stock prices, language modelling etc!
