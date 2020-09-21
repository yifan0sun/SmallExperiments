# SmallExperiments
A list of "sanity check" exercises for machine learning + optimization

conditioning2D.ipynb
 - Exploring how a bad condition number manifests trouble for first-order methods
 - Examines how different acceleration methods deal with this bad conditioning
 - 3 types of problems: simple quadratic (strongly convex but badly conditioned), logistic regression (not strongly convex), and Branin function (simple nonconvex function)
 - Everything is over 2-D inputs
 - Methods: GD, Polyak acceleration, Nesterov acceleration, Damped Newton, Chebychev acceleration, Adagrad, RMSProp, Adam
 - Easy to plug in new methods / problems
