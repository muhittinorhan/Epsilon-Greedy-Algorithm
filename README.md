# Epsilon-Greedy-Algorithm
The Epsilon Greedy algorithm is one of the key algorithms behind decision sciences, and embodies the balance of exploration versus exploitation. The dilemma between exploration versus exploitation can be defined simply based on:
Exploitation: Based on what you know of the circumstances, choose the option/action that has the best average return.
Exploration: Recognise that what you know of the different options may be limited, and choose to engage in options that may potentially reveal themselves to be of high return
The following analysis is based on the book “Bandit Algorithms for Website Optimization” by John Myles White. For further understanding of the code, I have included comments.
Below is the code for creation of the Epsilon Greedy algorithm setup and progressive updates of counts and values for arms.
Counts: Represent recorded times when arm was pulled.
Values: Represent the known mean reward. In the case of a Bernoulli arm, values represent the probability of reward which ranges from 0 to 1.
