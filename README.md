[//]: # (Image References)

<div>
<img src="images/agent.gif" width="500"/>
</div>


# Project 1: Navigation

### Introduction

This repository shows my Work on the first Project Navigation in the Udacity Deep Reinforcement Learning Nanodegree.
As you can see in the GIF above, it consists of an environment, where you have to collect yellow bananas to get positive rewards and avoid blue bananas as they would give negative rewards.

You can find the original instructions here: https://github.com/udacity/Value-based-methods/tree/main/p1_navigation

### Installation

1. Download the environment from one of the links below.  You need only select the environment that matches your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
    
2. Place the unzipped `Banana_Linux` folder in the root of this Repository
3. Install a Python 3.6 Environment on your host (the Unity Environment will only work with Python 3.6)
4. Create a virtual environment:`virtualenv -p /usr/bin/python3.6 your_environment` and activate it `source your_environment/bin/activate`
5. (When in activated virtual environment) Install the necessary packages from the requirements in this repo: `pip install -r requirements.txt`  

### Included Files

  * `images/`: includes all gifs and plots
  * `Navigation_Solution.ipynb`: shows my approach to solve this project
  * `Report.ipynb`: static result of the work in Navigation_Solution.ipynb
  * `dqn_agent.py`: includes the implementation of the Deep Q Network Agent (mostly based on the Udacity Code)
  * `model.py`: holds the implementation of the Deep Learning models that will act as the local/target Q Network training models
  * `simple_dqn_*`: are model checkpoints for four different models with different settings
    * `simple_dqn_six_layers_0990.pth`: QNetwork with five hidden layers and Epsilon Decay on 0.990
    * `simple_dqn_six_layers_0999.pth`: QNetwork with five hidden layers and Epsilon Decay on 0.999
    * `simple_dqn_three_layers_0990.pth`: QNetwork with two hidden layers and Epsilon Decay on 0.990
    * `simple_dqn_three_layers_0999.pth`: QNetwork with two hidden layers and Epsilon Decay on 0.999
