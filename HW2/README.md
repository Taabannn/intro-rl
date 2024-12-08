# Homework 2
Consider a bank that makes a loan based on people's job position and there are three different groups of customers, here are the amount of loans belonging to each individual category:
* For students: 5 million T
* For people with governmental jobs: 20 million T
* For self-employed people: 100 million T

The bank should get back the given money with a little amount of interest within a specified time. (The amount of interests respectively are 100000 T, 750000 T, 5 million T)

Each customer could return total amount of money with a definite probability.

First of all, I designed a model based on Multi-armed Bandit for maximizing bank's profit.

Secondly, Epsilon Greedy, Gradient-based and Upper Confidence Bound MAB agents has been implemented to maximize the received reward.

Lastly, the average reward and regret (for wanted hyperparameters like epsilon and learning rate) has been illustrated.