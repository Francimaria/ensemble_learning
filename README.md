### Exercicio-1

***It selected five public datasets with different characteristics and, for each dataset, 
calculated the Oracle in the test set for Bagging, Adaboost, Random Subspace (50\%), and Random Oracles,
changing the number of base classifiers ${10, 20, …, 100}$.
The Perceptron is used as a base-classifier, and it slit the datasets using 5-fold cross-validation.***

### Exercicio-2

It used two pruned approaches:

1) Using KDN

Assume three variants of the validation set

(a) Original dataset 𝒱;

(b) The dataset 𝒱’ with only difficult instances (kDN > 0,5) from 𝒱;

(c) The dataset 𝒱’ with only easy instances (kDN <= 0,5) from 𝒱.

3) Best first

### Exercicio-3

It evaluated different approaches from DESlib:

1) Static selection methods: SingleBest and StaticSelection
2) Dynamic Classifier Selection (DCS) methods: OLA, LCA, and MCB
3) Dynamic Ensemble Selection (DES) methods: KNORAU, KNORAE

Reference

Cruz, R. M., Hafemann, L. G., Sabourin, R., & Cavalcanti, G. D. (2020). 
DESlib: A Dynamic ensemble selection library in Python. J. Mach. Learn. Res., 21(8), 1-5.
