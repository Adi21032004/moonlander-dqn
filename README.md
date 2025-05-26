# moonlander-dqn
A Deep Q-Learning based AI agent trained to land safely on the moon using the OpenAI Gym's LunarLander-v2 environment.


https://github.com/user-attachments/assets/c930af0f-7280-457d-9405-d2322a1a211f




🚀 Overview

This project applies Reinforcement Learning, specifically Deep Q-Learning (DQN), to train an agent to solve the LunarLander environment. The agent learns optimal policies to control a lunar lander, achieving successful landings by maximizing cumulative rewards.

🧑‍💻 Technologies Used

Python

PyTorch for neural network implementation

OpenAI Gym for environment simulation

NumPy for data manipulation

🌐 Environment

LunarLander-v2 from OpenAI Gym

The goal is to land a lunar module gently between flags with minimal fuel usage.

⚖️ Model Architecture

Deep Q-Network (DQN)

Fully connected neural network

Replay buffer and target network

Epsilon-greedy exploration strategy

⚒️ How to Run

Clone the repository:

git clone https://github.com/yourusername/moonlander-dqn.git
cd moonlander-dqn

Install dependencies:

pip install -r requirements.txt

Train the agent:

python train.py

Watch the agent play:

python watch.py

🎯 Results

Solved the environment in ~500 episodes.

Average reward of 200+ over 100 consecutive episodes.

📅 Future Improvements

Add Double DQN / Dueling DQN

Integrate TensorBoard logging

Deploy trained model to web interface

🙏 Acknowledgments

OpenAI for Gym

Udacity for inspiration from their Deep RL Nanodegree

PyTorch for making life easier

Feel free to fork, open issues, or suggest improvements!
