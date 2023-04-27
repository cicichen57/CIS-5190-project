# CIS-5190-project
For this project, we are training and testing on the Electricity Transformer Dataset(ET Dataset) in order to predict the oil temperature for the future. If we are able to predict the oil temperature accurately, we can avoid unnecessary waste of electricity usage since the oil temperature can reflect the condition of the electricity transformer. We mainly implement Recurrent Neural Network, LSTM and linear regression models to predict the oil temperature. We also incorporate K-Fold Cross Validation into the RNN and LSTM model and feature augmentation into the linear regression model. Among these models, the one that works best is LSTM and RNN models with k-folder, which both have a MSE loss of 0.0014 on the testing set.
Moreover, we are doing some evaluations to test the performance of our models, including tuning different hyperparameters and adding Gaussian noise as the data shifts to the training data.
If the Milestone3.ipynb file does not compile correctly on github, please download the file and open it. 


