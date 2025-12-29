# BipedalWalker Reinforcement Learning

This repository contains reinforcement learning experiments on the
BipedalWalker-v3 and BipedalWalkerHardcore-v3 environments using PPO as well as SAC.

## Files

- `AISF_Application.ipynb`  
  Main project notebook. Includes:
  - PPO training
  - Reward shaping ablations
  - Hyperparameter tuning
  - Evaluation and plots
  - Hardcore environment experiments

- `AISF_Application_SAC.ipynb`  
  Exploratory notebook with alternative RL approaches and preliminary ideas
  that were used in the final model.

## Requirements

- Python 3.9+
- gymnasium[box2d]
- stable-baselines3
- torch
- numpy
- matplotlib

## Notes

Experiments were run in Google Colab using CPU execution.  
Paths referencing Google Drive can be adapted for local execution.
Code structure generated with assistance of LLMs.

## References

- Fujimoto et al., 2018 — Addressing Function Approximation Error in Actor-Critic Methods
- Ha et al., 2018 — World Models  
- Haarnoja et al., 2018 — Soft Actor-Critic: Off-Policy Maximum Entropy Deep Reinforcement Learning with a Stochastic Actor 
- Rudin et al., 2022 — Learning to Walk in Minutes Using Massively Parallel Deep Reinforcement Learning  
- Schulman et al., 2017 — Proximal Policy Optimization Algorithms   
