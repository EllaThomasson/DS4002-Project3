The data for this project comes from the MNIST Database from the Keras package. It can be read in in Python as follows:

**from keras.datasets import mnist**

**(X_train, y_train), (X_test, y_test) = mnist.load_data()**


It reads in with an automatic train/test split. If this predetermined split is not desired, it can be concatenated with the following code:

**X_combined = np.concatenate((X_train, X_test), axis=0)**

**y_combined = np.concatenate((y_train, y_test), axis=0)**




The Keras documentation can be found here: **https://keras.io/api/datasets/mnist/**
