[//]: # (Image References)

[image1]: https://user-images.githubusercontent.com/10624937/42135623-e770e354-7d12-11e8-998d-29fc74429ca2.gif "Trained Agent"
[image2]: https://user-images.githubusercontent.com/10624937/42135622-e55fb586-7d12-11e8-8a54-3c31da15a90a.gif "Soccer"


# Project 3: Collaboration and Competition

### Introduction

For this project, we worked with the [Tennis](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#tennis) environment.

The aim of this project was to implement and train agent/s to play table tennis. The two agents were provided control of rackets to bounce a ball over a net. A reward of +0.1 is given to an agent if it is able to hit the ball over the net. A penalty point of -0.01 is given when the ball hits the ground or his the ball out of the play area. 

This is an episodic problem where the goal is for the agent to continuously keep the ball in the air. The observation space contains the position and velocity of the ball and racket.

The environment is considered solved, when the average (over 100 episodes) of those **scores** is at least +0.5.

```
INFO:unityagents:
'Academy' started successfully!
Unity Academy name: Academy
        Number of Brains: 1
        Number of External Brains : 1
        Lesson number : 0
        Reset Parameters :
        
Unity brain name: TennisBrain
        Number of Visual Observations (per agent): 0
        Vector Observation space type: continuous
        Vector Observation space size (per agent): 8
        Number of stacked Vector Observation: 3
        Vector Action space type: continuous
        Vector Action space size (per agent): 2
        Vector Action descriptions: , 
```

The above environment details contains a space size of 8 and continuous action state space. 


## Instructions

1. The system requires python 3.6 installed in a python virtual envirnonment
```
conda create --name drlnd python=3.6
source activate drlnd

pip install ./python
```

1. Download the environment from one of the links below.  You need only select the environment that matches your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Soccer/Soccer_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Soccer/Soccer.app.zip)

2. Place the file in the `p3_collab-compet/` folder, and unzip (or decompress) the file. 