# Gradientdescent
Gradient descent is an optimization algorithm used to minimize the loss function of a machine learning algorithm.
it is a fundamental techniques used in the training various types of models ,including neural network.
the basic idea behind gradient descent is to iteratively update the  model's parameter in the direction that reduces the value of the loss function,eventually leading to a set of parameter values that result in a satisfactory model.
# basic rule of gradient descent
1. initialization: Start with an initial guess for the model's parameters. These parameters are typically represented as a vector, often denoted as θ or W (weights) and b (bias).
2. calculate loss:- Evaluate the loss function using the current parameter values.the loss function measures the discrepancy between the predicted outputs of the model and the actual targrt values.
3. compute gradients:- calculate the gradient of the loss function with respect to each model parameter.the gradient indicates the direction and magnitude of the steepest increase of thr loss.
4. update parameters:- adjust the model parameters in the opposite direction of the gradient descent to minimize the loss.this is done by subtracting a fraction of thr gradient from each parameter.the fraction isd etermined by a parameter called the learning rate.
5. Repeat:- repeat steps 2 to 4 for a certaion number of iterations ,until the loss function converges to a satisfactory level. 
