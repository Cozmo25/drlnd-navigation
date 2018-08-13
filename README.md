# DRLND - Navigation Project

Author: Ollie Graham  
Date: 13/08/2018

### About

[Banana Collector](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#banana-collector)

![Banana Env](images/banana-env.png)

### The Environment
For this project, you will train an agent to navigate (and collect bananas!) in a large, square world (see illustration of the environment above).

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. Given this information, the agent has to learn how to best select actions.

Four discrete actions are available, corresponding to:

Number of actions: 4
0. - move forward.
1. - move backward.
2. - turn left.
3. - turn right.

States look like:
```
[1.         0.         0.         0.         0.84408134 0.
0.         1.         0.         0.0748472  0.         1.
 0.         0.         0.25755    1.         0.         0.
 0.         0.74177343 0.         1.         0.         0.
 0.25854847 0.         0.         1.         0.         0.09355672
 0.         1.         0.         0.         0.31969345 0.
 0.        ]
 ```

States have length: 37

The task is episodic, and in order to solve the environment, your agent must get an average score of +13 over 100 consecutive episodes.

### Useage Instructions

To run the environment:

* First follow the instructions to install the ML-Agents package from Unity - Technologies [here](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Installation.md)
* Install the following Python packages (it's recommended to create a Virtual environment running Python 3.6 to install these packages to and work on the project in):
    * tensorflow==1.7.1
    * Pillow>=4.2.1
    * matplotlib
    * numpy>=1.11.0
    * jupyter
    * pytest>=3.2.2
    * docopt
    * pyyaml
    * protobuf==3.5.2
    * grpcio==1.11.0
    * torch==0.4.0
    * pandas
    * scipy
    * ipykernel
* Download the Unity Environment from the appropriate link listed here:
    * Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    * Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    * Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    * Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
* Then, place the file in the p1_navigation/ folder in the [DRLND GitHub repository](https://github.com/udacity/deep-reinforcement-learning#dependencies), and unzip (or decompress) the file
    * (For Windows users) Check out this link if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

    * (For AWS) If you'd like to train the agent on AWS (and have not enabled a virtual screen), then please use this link to obtain the "headless" version of the environment. You will not be able to watch the agent without enabling a virtual screen, but you will be able to train the agent. (To watch the agent, you should follow the instructions to enable a virtual screen, and then download the environment for the Linux operating system above.)
* After you have followed the instructions above, open Navigation.ipynb (located in the p1_navigation/ folder in the DRLND GitHub repository) and follow the instructions to learn how to use the Python API to control the agent.

Watch the (silent) video below to see what kind of output to expect from the notebook, if everything is working properly!

<a href="http://www.youtube.com/watch?feature=player_embedded&v=ltz2GhFv04A
" target="_blank"><img src="http://img.youtube.com/vi/ltz2GhFv04A/0.jpg"
alt="Example agent interacting with environment" width="240" height="180" border="10" /></a>



