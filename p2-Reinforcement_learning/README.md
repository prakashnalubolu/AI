# README.md

## Member 1

- BNumber: B01037579
- Name: saiprakash Nalubolu

## Description:
This project involves implementing various reinforcement learning algorithms to train an intelligent Pacman agent. The key components include Value Iteration, Q-Learning, and Approximate Q-Learning. This project demonstrates the implementation of Value Iteration, Q-Learning, and Approximate Q-Learning algorithms to train a Pacman agent. The agent learns to navigate and optimize its actions in various gridworlds and Pacman mazes.

## Implemented Functions:
Value Iteration Agent
Implemented in valueIterationAgents.py:
-runValueIteration: Performs value iteration for a specified number of iterations.
-computeQValueFromValues: Computes Q-value for a given state-action pair based on current values.
-computeActionFromValues: Determines the best action for a given state based on current values.

Q-Learning Agent
Implemented in qlearningAgents.py:
-getQValue: Returns the Q-value for a given state-action pair.
-computeValueFromQValues: Computes the maximum Q-value for a given state.
-computeActionFromQValues: Determines the best action for a given state based on Q-values.
-update: Updates the Q-value for a state-action pair based on observed transition.
-getAction: Chooses an action based on the epsilon-greedy policy.

Approximate Q-Learning Agent
Implemented in qlearningAgents.py:
-getQValue: Computes Q-value for a given state-action pair using feature weights.
-update: Updates the feature weights based on observed transition.

## Usage:
Value Iteration
To run the value iteration agent:

python gridworld.py -a value -i 100 -k 10

Q-Learning
To run the Q-learning agent:

python gridworld.py -a q -k 100

Approximate Q-Learning
To run the approximate Q-learning agent with identity features:

python pacman.py -p ApproximateQAgent -x 2000 -n 2010 -l smallGrid

To run the approximate Q-learning agent with custom features:

python pacman.py -p ApproximateQAgent -a extractor=SimpleExtractor -x 50 -n 60 -l mediumGrid

## Submission

- Link: `https://github.com/bu-cs-465-565/p2-saiprakash_nalubolu/tree/54ccf18af234c955b068086e66ac423c5de35c63`
