# INDE577
This github

Gradient descent & Neural Networks Parts 0
Gradient descent is a general iterative method for solving min(f(x)), where f(x) is some differentiable function. (First order method)
Global minimums basically impossible in general, so the best we can hope for is to find the local minimum.
Example, f(x) = (x-2)^2 +1 = x^2 - 4x +5, we have access to f(x) and f'(x). 
Initialize: X_0 = 4.0 (random guess) 
iterate X_1 = X_0 -alpha * f'(x), in machine learning, alpha is the learning rate, and in practice we do not care about how to optimize alpha, we can just try. 
let's set alpha = 0.25, X1 = 3 
X2 = 3 - 0.25* 2 = 2.5. 
X3 = 2.5 - 0.25 *1 = 2.25

