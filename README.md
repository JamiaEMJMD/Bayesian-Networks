This repository contains R code that solves the following problem using Logic Sampling(LS) and Likelihood Weighting (LW) algorithms. The problem involves computing probabilities of different events based on a Bayesian network.

# Bayesian Networks
A Bayesian network is a graphical model used in probability theory and statistics to represent relationships between random variables. It uses the Markov condition and a Directed Acyclic Graph (DAG) to represent how random variables are related. Markov condition in a Bayesian network specifies that a node is conditionally independent of its non-descendants given its parents, i.e. a node only depends on its parents directly, not on other nodes in the network. The direction of the edges in the DAG indicates the direction of influence or causality from parent nodes to child nodes.

# Bayesian Inference
The use of Bayesian Networks to estimate posterior probabilities, i.e. to use evidence (new observations or information) to update the probabilities (i.e., current knowledge) of the network, is known as the Bayesian inference. Exact inferences are only possible for small and medium networks. Exact inferences in large networks need prohibitively long computation times, as large Bayesian Networks address the problem of representing the joint probability distribution of a huge number of variables. To overcome the problem above with large Bayesian Networks, we use approximate inference techniques, which considerably shorten computation times while also providing good results.

# Logic Sampling (LS)
Logic Sampling is an approximate inference method for Bayesian Networks. It works by randomly sampling values for the variables in the network, considering the evidence provided, and then calculating probabilities based on these samples. LS provides an estimate of the desired probabilities by simulating multiple scenarios.

# Likelihood Weighting (LW)
Likelihood Weighting is another approximate inference technique for Bayesian Networks. It generates samples by taking into account the given evidence and assigns weights to each sample based on how consistent they are with the evidence. LW then uses these weighted samples to approximate probabilities, which can be used for inference in Bayesian Networks.

![First](https://github.com/JamiaEMJMD/Bayesian-Networks/blob/main/Bayesian%20Networks-1/images/im1.png)
![Second](https://github.com/JamiaEMJMD/Bayesian-Networks/blob/main/Bayesian%20Networks-1/images/im2.png)
