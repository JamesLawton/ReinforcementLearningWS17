# ReinforcementLearningWS17


To run the MSD system with the model-free algorithm PoWER -
Run the matlab script learn_dcp_incremental.m


To run the PPO Algorithm for the double pendulum - clone the repo and open a terminal from the main repo. 
You must have pybulletgym and openAI installed in order to run.

Run this command - python3 -m agents.scripts.train --logdir=/home/ --config=doublependulum

To run the PPO algorithm for the cartpole - navigate to PPO-Cartpole

Run this command - python3 -m baselines.ppo1.mujoco.py --env='CartPole-v0'



 
