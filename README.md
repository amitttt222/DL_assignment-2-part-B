# DL-Assignment-
# finetune a pre-trained model just as you would do in many real-world applications
    Assignment 2 part B Course Assignment of CS6910 Deep Learning IIT Madras
## Abstract<br/>
A feedforward neural network has been constructed entirely from scratch using the numpy library for all matrix and vector operations, without the use of any automatic differentiation packages.
## Dataset<br/>
The feedforward network that was implemented has been trained and tested using the Fashion MNIST dataset, which comprises of a training set containing 60,000 examples and a test set containing 10,000 examples. Each of these examples is a grayscale image of size 28x28 and is associated with one of the 10 available classes.
The top 3 hyperparameter configurations that were obtained for the Fashion MNIST dataset have also been used to train and test the network on the MNIST dataset.
## Objective<br/>
The aim is to implement multiple optimization techniques, including stochastic gradient descent, momentum-based gradient descent, Nesterov accelerated gradient descent, RMSprop, Adam, and Nadam. Additionally, the hyperparameters for these optimization techniques will be searched efficiently using wandb.
## Folder Structure<br/>
these below files contain the required code for first assignment
DL_assignment_question_1.ipynb<br/>
DL_assignment_question_10.ipynb<br/>
DL_assignment_question_4.ipynb<br/>
DL_assignment_question_7.ipynb<br/>
DL_assignment_question_8.ipynb<br/>
train.py<br/>
README.MD<br/>
## Results<br/>
The best test accuracy on Fashion MNIST dataset achieved is *87%* while on MNIST dataset is *92%*. The explanation and results of subproblems 
can be accessed (https://api.wandb.ai/links/cs22m010/3v658tom )
