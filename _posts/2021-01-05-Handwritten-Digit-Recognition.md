---
title: Handwritten Digit Recognition
date: 2021-01-05
tags: [Python,Jupyternotebook,DeepLearning,Tensorflow,NeuralNetworks]
---

<hr>
For this project I used the [MNIST Handwritten Digits dataset](http://yann.lecun.com/exdb/mnist/) which is commonly used in computer vision and deep learning.
I built a Multilayer Perceptron and used the Relu activation function for my hidden layers and Softmax Activation function for the output layer.  
After training the model on 50 epochs with a learning rate of 1e-3 I achieved a training accuracy of 99.2% and an accuracy of 97.84% on the test dataset.
Furthermore, I used Name Scoping and Image Visualization in Tensorboard to group nodes and ensure better visualization.

The jupyternotebook, histograms and graphs are attached below and here is the link to my [Github](https://github.com/Akarsh654/Deep-Learning-Projects/tree/main/Neural%20Networks/Handwritten%20Digit%20Recognition).
<hr>

Jupyter Notebook
<script src="https://gist.github.com/Akarsh654/7d6614731ec2694845c78d0c775d712d.js"></script>

Accuracy and loss, Graph
<img src="https://i.ibb.co/T425DkX/accuracy-and-loss.png" alt="accuracy-and-loss" border="0">
<img src="https://i.ibb.co/JBn956W/graph-run-512-DO-64-LR0.png" alt="graph-run-512-DO-64-LR0" border="0">

Histograms for all the layers
<img src="https://i.ibb.co/1TL2wQ2/layer-1-histogram.png" alt="layer-1-histogram" border="0">
<img src="https://i.ibb.co/hFbrKSg/layer-2-histogram.png" alt="layer-2-histogram" border="0">
<img src="https://i.ibb.co/kyYJYmq/out-histogram.png" alt="out-histogram" border="0">
