# Adam-vs-RMSProp-for-Nonlinear-Regression-using-ANN
Project compares Adam and RMSProp for nonlinear regression using ANN. Schaffer func. N. 4 generates dataset in Excel, normalized and split. ANN has 2 hidden layers, MSE loss, R2 tested. Results of RMSProp and Adam compared with relevant metrics.

Extended description:-

This project focuses on analyzing and comparing the performance of Adam and RMSProp optimizers for nonlinear regression using artificial neural networks. The Schaffer function N. 4 was used to generate a nonlinear dataset which was then saved into an Excel sheet. The data was then read from the Excel sheet, normalized between 0 and 1, and split into training, validation, and testing datasets.

An artificial neural network with two hidden layers and relu activation function was created in Python. The network was trained using Adam optimizer and MSE loss function. The mean squared error and R2 values were reported for the training data. The trained network was used to predict the outputs for the testing dataset and R2 values were reported for the testing dataset.

The same network was then trained using RMSProp optimizer and the performance was compared with Adam optimizer. Relevant metrics were reported to justify the observations.
