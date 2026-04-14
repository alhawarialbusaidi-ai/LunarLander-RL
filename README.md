🛠️ Technical Details
Environment: 

RL Algorithm: PPO (Proximal Policy Optimization)

Library: Stable Baselines3

Training Duration: 100,000 timesteps in Google Colab

Physics Engine: Box2D (Simulating gravity, wind, and thrust)

⚙️ Engineering Connection
As a Mechanical Engineering student, I used this project to explore how Artificial Intelligence can solve complex control problems.

Control Challenge: The agent must manage 3-axis thrust (Main, Left, Right) to counteract gravity and lateral momentum.

Optimization: Instead of manual PID tuning, the PPO agent maximizes a reward function based on fuel efficiency and landing velocity.

📂 Repository Contents
Lunar_Lander_PPO.ipynb: The full Python source code and training logs.

ppo_lunar_lander.zip: The pre-trained model weights (the "brain").

requirements.txt: Necessary libraries to run the environment.

🚀 How to Run
Open the .ipynb file in Google Colab.

Install dependencies:

Run the cells to see the trained agent in action!
