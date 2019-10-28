# K-Mean Clustering and using it for image compression
Support Vector Machines is a very powerful Machine Learning model,capable of performing linear or nonlinear classficiation,regression and even outlier detection. 
# Linear SVM Classfication



We have seen that for an SVM learning a linear classifier
f(x) = wtranpose*x + b
is formulated as solving an optimization problem over w :
min
w∈Rd ||w||2 + C X
N
i
max (0, 1 − yif(xi))
• This quadratic optimization problem is known as the primal problem.
