# Neural-Networks-Understanding
We will examine the effect of the removal of the standard scaler on the performance of the neural networks


a. Report the mean absolute error and the R2 for the training and testing datasets, 
generated randomly with a 75:25 split before and after removing the standard scaler. 
Present parity plots for the training and testing data. The remainder of the problem 
should be done without the standard scaler. 

b. Change the activation function from ReLU to sigmoid in the absence of the standard 
scalar. Report the performance metrics and show the parity plots. Which activation 
function performs better?

c. Using the better of the two activation functions, as determined in part (b), change the 
number of hidden layers in the neural network to 5 and 9. Report the performance and 
show the parity plots in the absence of the standard scalar. The code 
implemented in the in previous parts uses 1 hidden layer only. Assume 128 nodes in every hidden 
layer. What number of hidden layers gives the best performance?

d. Using the best value of the number of hidden layers found in part (c) and the better of 
the two activation functions found in part (b), change the number of nodes in every 
hidden layer to 64 and 256. Report the performance metrics and show the parity plots. 
Which number of nodes in the hidden layers gives the best performance?
