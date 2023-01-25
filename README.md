# da-python-deep-learning-poc



## :wave: Welcome

This project is a deep learning project implemented in Python using the Keras library. The project starts by importing the necessary libraries such as scipy, numpy, keras, glob and matplotlib. The project loads in .mat files and concatenates them to form the dataset for training and testing. The dataset is then divided into training and testing sets. After that, a visualization of a time series is plotted for demonstration.

The project then defines a sequential model using the Keras Sequential API. The model consists of three dense layers with 100, 50 and 2 neurons respectively, using sigmoid activation function. The model is then compiled using binary crossentropy as the loss function, and Adam optimizer, and binary accuracy as the evaluation metric.

The model is trained for 800 epochs on the training data and evaluated on the same data. The evaluation metrics are then printed out. Finally, the model is used to make predictions on the test data and the number of correct predictions is calculated, along with the overall accuracy of the model.
