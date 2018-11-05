# Project 1: Navigation

[image1]: https://user-images.githubusercontent.com/10624937/42135619-d90f2f28-7d12-11e8-8823-82b970a54d7e.gif "Trained Agent"

### Project Details

The aim of this project was to implement and train an agent to successfully navigate and collect yellow, and avoid blue bananas in a large virtual square world. The banana environment details can be found below in the code block.

```
Unity brain name: BananaBrain
        Number of Visual Observations (per agent): 0
        Vector Observation space type: continuous
        Vector Observation space size (per agent): 37
        Number of stacked Vector Observation: 1
        Vector Action space type: discrete
        Vector Action space size (per agent): 4
        Vector Action descriptions: , , , 
```

The above environment details contains 37 continuous values and 4 discrete actions (forward, backward, left, right). The problem is considered solved then the agent receives an average score of 13 on 100 consecutive episodes. 

## Instructions

1. The system requires python 3.6 installed in a python virtual envirnonment
```
conda create --name drlnd python=3.6
source activate drlnd

pip install ./python
```

1. Download the environment from one of the links below.  You need only select the environment that matches your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)

2. Place the file in the `p1_navigation/` folder, and unzip (or decompress) the file. 