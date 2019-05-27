# Project 2: Continuous Control


### Background

For this project, the Unity ML-Agents Reacher simulated environment was used to simultaneously train 20 agents with double-jointed arm to move to target locations. A reward of +0.1 is provided for each step that the agents’ hand are in the goal location.


### Environment Details
The state space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

The environment is considered solved if the 20 agents are able to receive an average reward (over 100 episodes) of at least +30.


### System Setup on Linux Machine
Step 1: Clone the DRLND Repository ([click here](https://github.com/udacity/deep-reinforcement-learning#dependencies) for more information)

Step 2: Download the Unity Environment ([click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Linux.zip) for more information)

Step 3: Place the file in the DRLND GitHub repository, in the `p2_continuous-control/` folder, and unzip (or decompress) the file.

Step 4: Clone the GitHub repository for this project into the `p2_continuous-control/` folder.

Step 5: Download and install Anaconda ([click here](https://www.anaconda.com/distribution/) for more information)

Step 6: Create and activate a virtual environment with the following libraries:

* UnityAgents (ver. 0.4.0) ([click here](https://pypi.org/project/unityagents/) for more information)
* Numpy ([click here](https://anaconda.org/anaconda/numpy) for more information)
* Random ([click here](https://pypi.org/project/random2/) for more information)
* Sys 
* Torch ([click here](https://pytorch.org/) for more information)
* Matplotlib ([click here](https://anaconda.org/conda-forge/matplotlib) for more information)
* Collections ([click here](https://anaconda.org/lightsource2-tag/collection) for more information)


### Instructions
Step 1: Start Jupyter Notebook

Step 2: Navigate to the folder for this project (in the `p2_continuous-control/` folder)

Step 3: Open the Continuous_Control jupyter notebook

Step 4: Change Kernel to 'drlnd'

Step 5: Run the cells as required 


### Other Information:

Refer to Report.pdf for more information on the learning algorithms, hyperparameters, architecture for neural network models etc.
