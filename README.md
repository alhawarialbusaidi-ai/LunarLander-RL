# LunarLander-RL
Autonomous rocket landing using Proximal Policy Optimization (PPO) and Gymnasium. An implementation of Deep Reinforcement Learning for thrust-vector control

Environment: Gymnasium LunarLander-v3

Algorithm: Proximal Policy Optimization (PPO)

Library: Stable Baselines3

Training: 100,000 timesteps in Google Colab

Physics Engine: Box2D simulation involving gravity, thrust-vectoring, and friction.

⚙️ Engineering Application
As a Mechanical Engineering student, I used this project to explore how Artificial Intelligence can handle complex control tasks that traditionally require manual PID tuning.

Control Challenge: The agent must manage 3-axis thrust (Main, Left, Right) to counteract gravity and lateral momentum.

Optimization: The model is rewarded for a "soft landing" (zero velocity at impact) and penalized for crashing or using excessive fuel.
