# 5054.mat, 7750.mat
These files contain the adjacency matrix filled by the passive query experiments run on the birds20 dataset. The
passive query experiments with a set 5054 edges are run 3 times. 
The majority vote generated adjacency matrix is stored in `5054.mat`. `7750.mat` is the adjacency matrix
generated by the passive query run on the birds20 dataset with every edge.
# allSportsDataForMatlab.mat
Contains the results from the all sports experiment, including the confusion matrix and crowdoworkers' answer.
# []_ground_truth.mat
Mat files ended with `_ground_truth` contain the ground truth vector. The number c on the i-th entry of the vector is the
cluster id of the i-th image, which also corresponds to the i-th row/col in the adjacency matrix.
# C_[].mat
Mat files started with `C_` contain the mask matrix used to select certain set of edges from the all sports adjacency
matrix. The number after the underscore represents the budget factor. Our budget is 60000, so `C_3` has 60000 / 3 =
20000 edges selected.
# repetition_count.mat
Vectors that used to plot a histogram to show the number of times a query has been repeated for the 4 experiments.
# pair_error_prob_[].mat
Mat files contain the pair error probability data for all the experiments.
# yun14_ground_truth_[].mat
Mat files contain the clustering ground truth for simulation ran by Yun14 and our algorithm.
# pair_prob_mat_[].mat
Mat files contain the pair probability matrix, which are used for yun14 related simulations.
