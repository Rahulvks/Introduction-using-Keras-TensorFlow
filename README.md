# Introduction-using-Keras-TensorFlow

#Model Explain 
#Data Set - https://www.kaggle.com/joniarroba/noshowappointments


#1: We use a constant seed for our random number generator to create the same pseudo-random numbers each time. This comes handy when we want to try different models and to compare their performances.

#2: Define the NN as with fully connected layers with 12 nodes each that are using the sigmoid function.

#3: Needed to use the TensorBoard tool to visualize the model training.

#4: Train our model using the defined optimizer and loss function. Epoch is the number of times (iterations) the whole data set will go through the network, validation_split is how much data from the dataset to hold back just to validate the performance of the model.
