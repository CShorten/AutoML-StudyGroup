I will add my code for the distributed learning rate search problem.

In this problem, there are 3 sections of the CNN with different learning rates, two portions of the stacked ResNet blocks and the final portion being the fully connected layers.

I am aiming to write this code such that it is easily integratable with different search spaces (such as changing the learning rate value range from (1e-1 to 5e-5) to something like 1e-1, 1e-3, ...), different search algorithms, and different evaluation techniques.
