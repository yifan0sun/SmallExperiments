# SmallExperiments
A list of "sanity check" exercises for machine learning + optimization

## Recommended for playing
conditioning2D.ipynb
 - Exploring how a bad condition number manifests trouble for first-order methods
 - Examines how different acceleration methods deal with this bad conditioning
 - 3 types of problems: simple quadratic (strongly convex but badly conditioned), logistic regression (not strongly convex), and Branin function (simple nonconvex function)
 - Everything is over 2-D inputs
 - Methods: GD, Polyak acceleration, Nesterov acceleration, Damped Newton, Chebychev acceleration, Adagrad, RMSProp, Adam
 - Easy to plug in new methods / problems

## Misc, accompanies talks
chebychev_accel.ipynb
 - staring at how the rescaled Chebychev polynomial "suppresses" inputs, at a faster rate than GD
 - simulates the distance to optimal in a strongly convex function, using GD vs Chebychev acceleration
 
