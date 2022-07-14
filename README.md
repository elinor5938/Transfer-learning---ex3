# Transfer-learning---ex3

This is an exersice taken from intro to ML course our task was to train a tranfer learning model that can classify 102 Oxford flowers dataset.
It contains 2 sections:

Part 1-ANN from Scratch

In this section we have added a neuron as additional layers to the single neuron model . Adding a layer improved the model in percent.
one layer accuracy  - 0.17%
Train MSE: 0.01 | Train Acc: 95.26% | Valid Acc: 94.32%

two layer model accuracy -
Train MSE: 0.01 | Train Acc: 95.43% | Valid Acc: 94.66%

Part 2 -Practice the usage of CNN (Convolutional Neural Network)

In this section we implemented two pre - trained deep neural networks models as following:
 -Mobile Net V2
 - VGG16 contains two files each represents different seed 
In each model we first split the data for training (50%) ,validation ( 25%) and test (25%) .The splits were executed twice for each in a different seed for both models.
