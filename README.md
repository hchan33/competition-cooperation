# Project 3 : Collaboration & Competition

### Introduction

For this project, we will work with the [Tennis](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#tennis) environment.

In this environment, two agents control rackets to bounce a ball over a net. If an agent hits the ball over the net, it receives a reward of +0.1. If an agent lets a ball hit the ground or hits the ball out of bounds, it receives a reward of -0.01. Thus, the goal of each agent is to keep the ball in play.

### Training

This project will use two indepedent agents with shared replay buffer and critic. Each agent will also has access to the states of the ball and the opponent, but from its own point of view.

### Solving the Environment

The task is episodic. A solution is considered valid if the agent achieves an average score of +0.5 over 100 consecutive episodes.

### Getting Started

1. Download the environment from one of the links below.  You need only select the environment that matches your operating system:
        - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Linux.zip)
        - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis.app.zip)
        - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86.zip)
        - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86_64.zip)
  
2. Place the file in ‘p3_collab-compet/` folder where ‘CC_ddpg.ipynb’ is located and unzip (or decompress) the file. Note the location of ‘Tennis.exe’ in ‘..\Tennis_Windows_x86_64\Tennis_Windows_x86_64\Tennis.exe’

### Instructions

Open Anaconda Prompt. Navigate to the folder where ‘CC_ddpg.ipynb’ file is located. Type ‘conda activate drlnd’ to activate the environment and load relevant packages. Then type ‘jupyter notebook’. A web browser will appear with the Jupyter homepage. Select ‘CC_ddpg.ipynb’. Enter the path to ‘Tennis.exe’ in the second code window. Go to Cell tab in the menu bar and select Run All. If a package is missing during code execution, exit back to prompt and type ‘conda install package-name’. The restart Jupyter Notebook.  

