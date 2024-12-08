# Homework 3
A map of 6 $\times$ 6 frozen lake is given. There is only one safe path from the start point to the goal and each state of it may be broken with probability of 0.001, if the agent enters in it. The reward of reaching goal is 100, 
the agent receives reward of -1 for each movement and also if it falls into broken states, it earns -10 points and the game will be finished.

The allowed direction of movements for the agent are LEFT, DOWN, RIGHT and UP. In part 1, the agent enters the desired state with probability of 0.94 and may slip to another one with 
probability of 0.06. The value of each state has been obtained and illustrated by utilizing both policy and value iteration-based agents. The impact of threshold $\theta$ on convergence rate for both 
algorithms has been plotted as well. 

In part 2, the agent enters the desired state with probability of 0.7 and may slip to another one with probability of 0.3. Again the value of each state under new condition has been obtained 
and illustrated by utilizing both policy and value iteration-based agents and the impact of $\theta$ on convergence rate for both algorithms has been plotted as well.

In part 3, the map has been extended to 15 $\times$ 15 and all the same procedure has been repeated under condition of part 2.