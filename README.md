# WordZapper RL Agents

This repository contains two separate reinforcement learning projects for the **WordZapper** game from the Arcade Learning Environment (ALE):

## Algorithms

1. **Deep Q-Network (DQN)**: 
   - A Q-learning approach using a deep neural network to learn optimal actions based on image-based observations.
   - Trains the agent using experience replay and a target network to stabilize learning.

2. **Proximal Policy Optimization (PPO)**: 
   - A policy gradient method that improves gameplay by optimizing the policy directly.
   - Uses clipping in the objective function to ensure that the policy updates do not deviate too much, providing stable learning.

## Libraries Used

- **gymnasium**: For the WordZapper environment.
- **ale-py**: To handle ROMs and communicate with the Arcade Learning Environment.
- **PyTorch**: For building and training deep learning models.
- **numpy**: For numerical operations.
- **matplotlib**: For plotting training results.
- **CV2**: For image processing.
- **tqdm**: For displaying progress bars during training.
