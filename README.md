# Markov Decision Process Generator

The provided Python code implements a basic Markov Decision Process (MDP) framework that allows users to define the structure of an MDP by specifying the number of states and actions, along with the transition probabilities and rewards associated with each state-action pair. At the core of the implementation is the MDP class, which initializes the MDP by either generating random transition probabilities or allowing users to input their own. This flexibility enables users to simulate various decision-making scenarios. The transition probabilities are stored in a three-dimensional NumPy array, normalized to ensure that the probabilities for transitioning from a given state to all possible next states sum to one. The rewards can also be user-defined or randomly generated. The code includes a visualization method that utilizes the NetworkX and Matplotlib libraries to create a directed graph representation of the MDP. In this visualization, states are represented as nodes, and the transitions between them, labeled with the corresponding actions and probabilities, are depicted as directed edges. This visual representation aids in understanding the dynamics of the MDP by clearly illustrating how actions influence state transitions and the associated rewards, making it a valuable tool for educational and research purposes in reinforcement learning and decision-making analysis.
