# Neural_Network_Charity_Analysis

## Analysis Overview
The purpose of this project is to use deep-learning neural networks with the TensorFlow platform in Python, to analyze and classify the success of charitable donations.
We use the following methods for the analysis:

preprocessing the data for the neural network model,
compile, train and evaluate the model,
optimize the model.

## Resources
Data Source: charity_data.csv
Software: Python 3.7.7, Anaconda Navigator 1.9.12, Conda 4.8.4, Jupyter Notebook 6.0.3

## Results
“IS_SUCCESSFULL” column is the target.

Target variables are also known as dependent variable and we are using this variable to train our ML model.

Variables include all columns, except target variable and the one(s) we dropped “EIN" and "NAME” in the first trial and “EIN” in optimization trial.
The variables that should be removed and are neither targets nor features are variables that are meaningless for the model.

The variables that don’t add to the accuracy to the model. One of the examples would be variables with all unique values.

Another thing to keep in mind is to take care of the Noisy data and outliers.

We can approach to this by dropping outliers or bucketing.

This deep-learning neural network model is made of two hidden layers with 80 and 30 neurons respectively.
The input data has 43 features and 25,724 samples.
The output layer is made of a unique neuron as it is a binary classification.
To speed up the training process, we are using the activation function ReLU for the hidden layers. As our output is a binary classification, Sigmoid is used on the output layer.
For the compilation, the optimizer is adam and the loss function is binary_crossentropy

