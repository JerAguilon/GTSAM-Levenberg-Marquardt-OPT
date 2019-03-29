# Malloc-Free-Levenberg-Marquardt

This is a malloc-free Levenberg-Marquardt optimizer for nonlinear least squares regression.
It comes with a demonstration fitting an arbitrary nonlinear function. This is a subproject
for [GTSAM](https://bitbucket.org/gtborg/gtsam/), a smoothing and mapping library as a 
part of my undergraduate research.

# Dependencies

* [Eigen 3.3](http://eigen.tuxfamily.org/index.php?title=3.3) 

# Running the demo

From the root of the project:

1. `mkdir build/`
2. `cd build`
3. `cmake ..`
4. `make && ./LMSolver`
