# Prototypical Networks are Linear Classifiers !

Hi everyone,

This blog post we will discuss how the popular prototypical networks can be viewed as linear classifiers. 
[Prototypical Networks](https://arxiv.org/pdf/1703.05175.pdf) are one of the most common few shot learning methods use to learn a classifier that can 
generalize well to classes not seen during training time.

The idea is simple !
1. Learn an embedding space (also called metric space in the paper) where the samples from same class are closer and those from different classes are far away.
Thus, we are trying a learn a discrimatory embedding space.
