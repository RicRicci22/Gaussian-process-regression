# Gaussian-process-regression
Trying to understand Gaussian process regression

Resources:
- https://towardsdatascience.com/understanding-gaussian-process-the-socratic-way-ba02369d804.


KERNEL
The kernel is used to model the covariance between two random variables at different locations f(x1) and f(x2). It seems reasonable to have a prior that model the covariance between locations giving high values to neighboring locations, while low values to far apart locations. In this way the random variable is seen to vary "smoothly" between all the possible locations. Also in this way, if one has prior knowledge about how values at some point affects value at other points, one can incorporate this knowledge into the covariance function. 
