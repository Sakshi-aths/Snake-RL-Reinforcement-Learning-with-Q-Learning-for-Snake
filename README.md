# Snake-RL-Reinforcement-Learning-with-Q-Learning-for-Snake

This project uses Q-Learning, a key technique in reinforcement learning, to create a Reinforcement Learning agent that learns to play the traditional Snake game. It trains the agent over episodes by combining effective Q-value updates with exploration and exploitation tactics, with the ultimate goal of maximizing the score while avoiding collisions.

### Features

- **Custom Snake Environment**: A Python-based setting created using **Pygame** that offers visual cues when playing and training.
- *Agent for Q-Learning**:

Adjustable parameters for **learning rate**, **discount factor**, and **exploration decay** are available in tabular Q-learning.

Adaptive **epsilon-greedy exploration** using sophisticated tactics, such as weighted random actions based on temperature.

For more consistent learning across episodes, replay memory is used.

The game's essential state features, including the location of the snake, food, and collision hazards, are encoded via the dynamic state representation.

Features like tracking steps in a single direction to penalize recurrent conduct are among the improvements.

- **Visualization**: - - The game is rendered in real time while being played and trained.

Plotting performance measures (epsilon decay, average scores, and scores) automatically to monitor learning progress.

- *Modes**:

- **Train**: Save the progress of a newly trained agent.

- **Play**: See an autonomously trained agent play the game.
