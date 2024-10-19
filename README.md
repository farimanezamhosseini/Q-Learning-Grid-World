# Q-Learning-Grid-World
This project implements a simple Q-learning algorithm in a 5x5 grid world environment. The agent's goal is to navigate from a starting position to a goal while avoiding holes that result in a loss.  The notebook contains the following key components:

Environment Setup: A 5x5 grid with start, goal, and hole states.

Q-Learning Agent: Implements the Q-learning algorithm, allowing the agent to learn optimal moves by updating its Q-values through exploration and exploitation.

Reward System: Rewards are provided for reaching the goal, with penalties for falling into holes.

Visualization: After training, the notebook plots the reward over episodes and prints the learned Q-values for each state.
