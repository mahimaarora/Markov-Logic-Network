# Markov-Logic-Network
## An Interface Layer for Artificial Intelligence
###### An Application of MLN

A Markov logic network (MLN) is a probabilistic logic which applies the ideas of a Markov network to first-order logic, enabling uncertain inference. Markov logic networks generalize first-order logic, in the sense that, in a certain limit, all unsatisfiable statements have a probability of zero, and all tautologies have probability one.

This project proposes a simple approach to combine first-order logic and probabilistic graphical models in a single representation. Markov logic network (MLN) accomplishes this by attaching weights to first-order logic formulas (or clauses). Using the concept of MLN, Personalized PageRank is implemented on the dataset describing the Roman city of Pompeii. Inspired by “Google Sets” and Bayesian sets, the problem considered is of retrieving complex objects and relations among them, given a query consisting of a few atoms from that concept. This problem is formulated as a within-network relational learning problem using few labels only and describe an algorithm that ranks atoms using a score based on random walks with restart(RWR). The features used re-personalize the original RWR and finally compute the set completion, based on Label Propagation

[Reference](http://www.first-mm.eu/files/neumann11aaai.pdf)
