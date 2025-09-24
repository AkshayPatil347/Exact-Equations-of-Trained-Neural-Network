# Exact-Equations-of-Trained-Neural-Network

Below Paper is basis of Implementation of this work

Paper Link - https://www.researchgate.net/publication/391476156_Getting_Exact_Functions_of_Neural_Network_and_Making_them_Interpretable_Akshay_Patil_Founder_and_CEO_of_Heisenberg_Quantum_AI

Note - Different loss functions with different optimization algorithms as well as the initialization of weights and biases play crucial role in identifying how many common functions per m data points are training exist.

These common function per m data points can used in input training data compression , i.e. to remove those data points which have common functions , which compresses the data , this along with the paramterizing the data points to replace the data by function can be useful tools for identifying the sufficient statistics for training deep neural metworks.
Also for quantifying the uncertainty in prediction of the deep Neural Networks by identifying which training data points are close or far away one can use Bayesian deep NN particularly Laplace approximations to quantify how much uncertain prediction of deep NN is. One can also relate it to the paths of NN as a tree strcuture which is explained in our Deterministic Interpretation of NN Research Paper , i.e. (this is Probabilistic Interpretation of NN) some paths belonging to class m may be classified as class m , but the input training data may completely be out of distribution if the training dats of the M th class , so To quantify this uncertainty Approximate methods such as Laplace Approximations or MCMC (but require large path exploration i.e. (large number of pseudo data inferences on the trained NN which is O(n**2) to predict the class) , before converging which is practically not possible as number of paths of NN is quite large.)(Reference for Laplace Approximation - Lecture 13 , Uncertainty in Deep Learning By Phillip Henning , in Numeric Machine Learning,  Youtube Lectures)
