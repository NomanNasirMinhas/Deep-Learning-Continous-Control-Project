# Deep-Learning-Continous-Control-Project
In this project we will train a double-jointed arm so that it can move to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of our agent is to maintain its position at the target location for as many time steps as possible.

# Environment
The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

# Goal
Our agent must get an average score of +30 (over 100 consecutive episodes, and over all agents). Specifically,
- After each episode, we add up the rewards that each agent received (without discounting), to get a score for each agent. This yields 20 (potentially different) scores. We then take the average of these 20 scores.
- This yields an average score for each episode (where the average is over all 20 agents).
**The environment is considered solved, when the average (over 100 episodes) of those average scores is at least +30.**

# Dependencies
We will require following packages to run this project.
1. **deep-reinforcement-learning  (DRLND)**
2. **ml-agents  (ML-Agents Toolkit)**
3. **Unity environment _Reacher_**

# How to train agent
Run each cell of the notebook sequentially to train the agent.

# Weights of the trained agent
The **weights** of the trained agent are saved into the files **_checkpoint_actor.pth_**  and  **_checkpoint_critic.pth_**.

# Acknowledgements
This code has been improved with help from code provided by Udacity and from Udacity Knowledge forum discussions.