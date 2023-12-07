# Anomaly-Detection-using-Autoencoders
An autoencoder to classify bank transactions as fraudulent or not 


## Topic
In this notebook I will experiment with neural networks to classify bank transactions as fraudulent or not. The neural net I will be using is the autoencoder which is a simple network that
learns to recreate its input, its performance is measured with the error between the actual input and the input recreated by the autoencoder. After data preprocessing, the autoencoder is
only fed with the non fraudulent instances until the error is minimized as much as possible, then the autoencoder is fed fraudulent instances for which the error will be higher than the
non fraudulent instances that it has learned to recreate, and that's how we can classify an instance as fraud or not. So let's get started !

## Objective
- Create a network that is able to classify a transaction as a fraud or not

## Summary
- Importing libraries
- The dataset
- Data preprocessing
- Creating the data loader
- Creating the Autoencoder
- Training the network
- Network evaluation
- Testing the network
- Evaluation metrics
- Conclusion

## Libraries
- Pandas
- Numpy
- Sklearn
- Torch

## Data source
https://www.kaggle.com/datasets/dhanushnarayananr/credit-card-fraud?fbclid=IwAR0BBhLKaB8Xdahb3lbx9R8HVV0ceXkIP5WFmPcv8wO6VGfBPusPRmODTJI
