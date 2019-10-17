# Udacity Deep Reinforcement Learning Nanodegree Project 1: Navigation

### Project details

Project created as 1st project on Udacity Deep Reinforcement Learning nanodegree.<br>
The goal of the agent is to gather `yellow` bananas while avoiding the `blue` ones.<br>

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.  

- **State space** is `37` dimensional and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction.

- **Action space** is `4` dimentional. Four discrete actions correspond to:
  - `0` - move forward
  - `1` - move backward
  - `2` - move left
  - `3` - move right

- **Solution criteria**: the environment is considered as solved when the agent gets an average score of **+13 over 100 consecutive episodes**.

### Getting Started

1. Download the environment from one of the links below.  You need only select the environment that matches your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)

    (_For Windows users_) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

2. Place the file in root of the folder and unzip the file.

3. Run all the cells in [Navigation.ipynb](Navigation.ipynb) to test the environment.

### Instructions

To train the agent run all the cells in [Navigation.ipynb](Navigation.ipynb) notebook.

Description of the implementation is provided in [report.md](report.md).
For technical details see the code in the notebook.

Model weights are stored in [checkpoint.pth](checkpoint.pth)
