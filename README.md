# AI From Scratch

Sure, I would never ACTUALLy implement a large neural network from scratch. But I think that doing it once (and only once!) gives you a more intuitive understanding about models, and therefore better ability to design & debug new models. 

This work is heavily inspired by Deeplearning.AI & Andrew Ng's Machine Learning specialization on Coursera. Here is my current progress.

### Current Work:
Advanced Learning Algorithms: Week 3

### Certificates:
Supervised Machine Learning: Regression and Classification


## Projects

### Linear Regression

In the file `linear-reg.ipynb`, I used a dataset of random numbers from Kaggle, and implemented a linear regression model. This involved coding:

1) The loss function (Mean Squared errors)
2) Gradient Descent calculation
3) Model training/Parameter Updating

This gave me a better understanding of what "training a model" actually means, as well as how to pick & the importance of picking a good learning rate. 

### Artificial Neural Network

In the file ANN.ipynb, I created a Neural Network with Tensorflow to recognize handwritten numbers from the MNIST data set.

After the Tensorflow implementation, I coded my own Neural Network implementation, with forward propogation (Using the weights from the Tensorflow implementation to continue forward). This taught me about activation functions, feature scaling, and vectorization optimizations for Neural Networks.

In ~struggling~ building a Neural Network myself, I gained a better understanding of what the dimensions of a weight matrix mean (beginning this project, I could not remember for the life of me of whether it was input_size by output_size or output_size by input_size)

