# Stock-Prediction-using-Artificial-Neural-Networks
This was a project done for 
In it, i was answering the question of which neural network is best for stock prediction (time-series).
The developed models are:
1) Convolutional Neural Network (1D and 2D)
2) Recurrent Neural Network
3) C-RNN (1D convolution before sending the values to the RNN)
4) Generative Adversarial Neural Network
The process went as follows:
1) CNN 1D: In this model, I inserted the stock prices into the model by using 1D convolution to 
   extract features from the stock, and predict on them. Average pooling was used too.
2) CNN 2D: In this model, I transformed the stock to an image in order to use the regular 2D convolution.
   Gramian Angular Field was used to transform the stock to an images.
3) RNN: The traditional way for stock prediction
4) C-RNN: 1D convolution was used to extract features from the stock, and then insert those values into the RNN for better prediction.
5) Generative Adversarial Network: In this model, a generative RNN was used, and a CNN discriminator. The idea was to model the behaviour
   of a typical person, where he predicts some future stock prices, and then looking on the previous data, discriminates whether it is
   real or fake.
The results and more information is in the paper, poster, and notebooks. :)
