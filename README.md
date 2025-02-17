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

**6-imdb-kagglemodel**

TensorFlow Hub and Kaggle are two platforms that provide pre-trained models and datasets. Instead of designing models from scratch, we can easily leverage these resources to use ready-made models and datasets for various tasks.New items:
- Using Kaggle ready models
- tf_keras like keras in tensorflow

**7-flowers-Augmentation**

Data Augmentation is a technique to increase data (audio, text and image) which leads to better learning of the model. In this code, there is a dataset related to the images of 5 types of flowers and we use this technique. New items:
- Data Augmentation for image--> tf.keras.layers & tf.image
- RandomFlip ,RandomRotation ,RandomZoom ,RandomContrast

**8-fashion_mnist-hypertuning**

With the hyperband method, we want to determine the best hyperparameter (the best number of epochs, rl, and number of neurons). New items:
- srop early
- hypertuning --> epochs,rl ,Number of neurons
- hyperband method

