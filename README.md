# cifar_10

<h1>Neural Network-Training And Evaluation</h1>
The specific task we are trying to solve is image classification. We will be using a very commong
dataset called CIFAR-10 that has 60,000 images (50,000 for training and 10,000 for testing)
separated into 10 classes (link for Keras , link for Pytorch). The classes are

airplane
automobile
bird
cat
deer
dog
frog
horse
ship
truck

In this task, you will:
Use a modern machine learning library (Pytorch/TF/Keras)
Writing the chosen library-specific code.
Evaluating neural network models.
Create three neural network models and train each for the classsification task above, where each of
the models described should be a different Python class with the specified name.

<h2>NetA</h2>
The first neural network will be the simplest, in that it has no hidden layers. It should take the image
and flatten it to a vector for the input, and then have 10 outputs, one for each class.
There should be no non-linearities for this network and is just a very simple linear classifier.
<h2>NetB</h2>
The second neural network will be slightly more complicated in that it has a hidden layer with 300
nodes and adds a non-linearity between the layers. It should use the following operations in this
order:
Flatten the image to a vector for the input
Use a fully-connected linear layer with 300 hidden-neurons
Use the ReLU activation function
Use a fully-connected linear layer to the 10 outputs.
Neural Network-Training And Evaluation
7/30/2021 BasicNeuralNetwork-TrainingAndEvaluation.ipynb - Colaboratory
https://colab.research.google.com/drive/1qD8Z6RXVzch4eTWoru19_AtvtrPsZc4A#scrollTo=JJORzpttqKNl&printMode=true 
<h2>NetC</h2>
This third neural network will be a convolutional neural network. It should use the following
operations in this order:
Use a convolution layer with kernel-width 5 and depth 25
Use the ReLU activation function
Use a max-pool operation with kernel-width 2 and stride 2
Flatten the image to a vector for the next step's input
Use a fully-connected linear layer to the 10 outputs.
