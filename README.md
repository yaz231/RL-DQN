# RL-DQN
Reinforcement Learning Environment using Gymnasium and DQN


Everything is done using Torch. Currently have Deep Q Network setup in DQN.py.

To run, run rl.py. It will automatically search for the .pth files for a specific Gymnasium environment (in this case Lunar Lander or Cartpole).
If the .pth files exist, it will render the game state for the user for 5 episodes. If those files are deleted, it will train the agent against the environment and update the model for 600 episodes, at which point it will save the configuration as new .pth files.
