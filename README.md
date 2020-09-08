# Navigation

TASK:

In this project we aim to solve an environment where we have to move around in an arena trying to collect yellow bananas while avoiding blue bananas.
Indeed a reward of plus 1 is given for a yellow banana, while a reward of minus 1 is given for a blue banana.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available.

The task is episodic, and in order to solve the environment, your agent must get an average score of +13 over 100 consecutive episodes.

DEPENDENCIES AND LIBRARIES TO INSTALL:

The libraries to install, assuming python is present on your machine are

Open Ai gym. A minimal installation can be obtained running "pip install gym" on your terminal.
Pytorch An installation can be obtained running "pip3 install torch torchvision"
Unity Environments for which one can follow the link https://secretlab.institute/2019/07/11/installing-unity-ml-agents/
Numpy if it is not already installed.

The code in the Jupyter notebook, which contains all the parts of the modified DDQN algorithm useful to solve the environment, can be run from top to bottom.
The algorithm contains basic DDQN with an addition of a dueling architecture, which is useful to decouple the learning of the value of the single action from the learning of the state.
