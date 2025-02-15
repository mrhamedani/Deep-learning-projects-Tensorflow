# Deep-learning-projects-Tensorflow

**1-Cars-Neural-network**
In this code, we wanted to train a dataset in the neural network and make predictions by regression. New tips:
- Structure of neural network model (epoch, neuron, optimizer, loss, compile, fit , layer , Sequential,...)
- Analysis of loss behavior (for set weights) and loss validation in train (for set hyperparameter & Not overfitting)
- Dense layer for regression & Normalization layer
- Data analysis with seaborn & evaluate

**2-breast-cancer-Neural-network**
In this dataset, we perform classification by neural network and predict the test data and measure the accuracy in training, testing and validation.
New items:
- optimizer, Adam or SGD?
- sigmoid layer & binary_crossentropy loss for  binary classification
- Scaling or Normalization?

**3-MNIST-ComputerVision**
A common example for computer vision from the MNIST dataset (numbers 1-9 as labeled black-and-white photos) New items:
  - using layers.Flatten 
  - using onehotencoding for model
  - history method & categorical_crossentropy loss

**4-cifar10-ComputerVision**
A common example for computer vision from the cifar10 dataset (10 photo classes such as dogs and cats, etc. with labels) New items:
- CNN --> Conv2D & MaxPooling2D layers
- utils.to_categorical

**5-imdb-RNN(LSTM)**
Using an advanced Recurrent Neural Network (RNN) model called Long Short-Term Memory (LSTM), we classify the IMDB movie reviews dataset into positive and negative sentiment classes. Additionally, we perform predictions on new reviews.New items:
- RNN(LSTM) architecture
- map, constant , expand_dim , GlobalAveragePooling1D leyar
- TextVectorization
- Embedding
- standardization text by regex
