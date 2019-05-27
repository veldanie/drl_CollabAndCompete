# About this project

This repository contains the solution to the Tennis Unity Environment ([github repository](<https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#tennis>)). In this environment, two agents play tennis and bounce a ball over a net. This project is part of Udacity's [Deep Reinforcement Learning Nanodegree](https://www.udacity.com/course/deep-reinforcement-learning-nanodegree--nd893) program. The goal is that both agents keep the ball in play. If an agent hits the ball over the net receives a reward of +0.1, otherwise receives a reward of -0.01.   

The action space has 2 dimensions and each variable corresponds to a number between -1 and 1.  The state space dimension is 8.  This an episodic task. The environment is considered solve if the average score over 100 consecutive episode surpasses +0.5. For each episode, the score corresponds to the maximun over the scores of both players.  



# Getting Started

1. Download the environment from one of the links below.  You need only select the environment that matches your operating system:

    ### One Agent

    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86_64.zip)

    

    Place the file in the repository directory, and unzip (or decompress) the file.

    

# Instructions
The file `dqn_agent.py` corresponds to the agent class and includes the methods for interacting with the environment and training the agents. `model.py` contains the neural network architecture.   `Tennis.ipynb`displays the solution. 
