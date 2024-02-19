# Research-on-Neural-Network-Performance
Evaluating with full factorial design the impact of hyperparameters on a neural network's performance based on MNIST written numbers dataset 

Since the first day I learned about the importance of hyperparameters in machine
learning, I have been curious about whether there is an optimistic solution for the setting of
hyperparameters for all environments. However, when the situation changed, the
settings of hyperparameters needed to be altered to accommodate new models and
data. There seems always to be a trade-off between efficiency and accuracy, precision
and complexity. What this paper mainly talked about is evaluating the impact of four
hyperparameters on neural networks with the MNIST dataset through a statistical
modeling process. By doing the Full Factorial Design at Two Levels with detailed
analysis, the property of neural networks and MNIST dataset is examined. Learning
rate and number of layers are taken to be the two significant main effects on accuracy,
with the instability of the learning rate during the training process, the number of layers may
be the more influential one. The batch size is relatively not important, and the other
three hyperparameters are more determinant in the case of the MNIST dataset. In this
experiment, I also found the interactions between different hyperparameters can be very
interesting, and their inter-changing reveals some of the thorough properties of neural
networks.
This experiment is a complete study in the sense of Full Factorial Design. However,
there are always more things to do. When evaluating the location and dispersion effects,
the experiments refer to a visual approach for better intuitionistic understanding, but I
did not employ the numerical approach to calculate the exact number following
regression equations. In the future, I will conduct more experiments for more activation
functions and other factors related to getting a better sense of fine–tuned hyperparameters
in the field of machine learning.
