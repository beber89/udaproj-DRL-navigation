# Project 1: Navigation - Deep Reinforcement Learning

## Project Details

---

- **states**: The state space is comprised of 37 dimensions, it contains the agent's velocity, along with ray-based perception of objects from the agent's point of view
- **action_space**: Four action spaces (basically navigation tasks)
  - *Forward* might be ignored since the agent moves forward if no action is chosen.
  - *Backward*
  - *Left*
  - *Right*
- **goal**: The environment is considered solved if agent gets an average score of +13 over 100 consecutive episodes

## Getting Started

---

- Clone the repo

- Install python dependencies
  - pytorch `pip install torch`

  - matplotlib `pip install matplotlib`

  - unityagents `pip install unityagents`

- Download the unity environment
  - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
  - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
  - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
  - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)

## Instructions

---

### Training

- Click `Cell` in the menu bar then click `Run Cells`.

### Run Trained Agent

- Run all the cells before `My Workspace` section

- Run all the cells starting beneath the `Watch the agent play` section

- This loads the weights into the model from file `checkpoint.pth`

- Watch the agent play in a new unity window

![gameplay](game-record.gif)
