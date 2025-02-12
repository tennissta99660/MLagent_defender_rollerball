# RollerAgent vs DefenderAgent 🏆

This project is a reinforcement learning (RL) environment built in Unity using ML-Agents. A **RollerAgent** is rewarded for reaching a target, while a **Defender** attempts to block it. The goal is to train the Rolleragent to optimize it's respective behaviors through reinforcement learning.

## 🚀 Features
- **RollerAgent:** Tries to reach and collide with the target to receive a reward.
- **Defender:** Moves to block the RollerAgent from reaching the target.
- **Training with ML-Agents:** Uses Unity ML-Agents to train Rolleragent through reinforcement learning.
- **Custom Reward Function:** Encourages RollerAgent for successful collisions and penalizes failures(when colliding with the Defender)

## 🛠 Setup & Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Unity-Technologies/ml-agents.git
   ```
2. Go to the Installation guide in this repository and follow it step by step for proper installation.

## 🎮 How It Works
- The RollerAgent moves on a plane towards a randomly placed target.
- The Defender attempts to block/attack it using it's c# script.
- Rewards:
  - RollerAgent gets a reward for reaching the target.
  - RollerAgent gets penalized for colliding with Defender in order to make it learn to dodgee Defender. 

## 🔥 Technologies Used
- **Unity ML-Agents** – Reinforcement learning framework
- **Python** – Training models & configuring ML-Agents(Though you wont be required to write any code in python.)
- **C#** – Game logic and agent behaviors
- **TensorFlow/PyTorch** – Backend for training models(Pytorch is used, and TensorFlow is used to monitor the Agent's performance during training.)

## 📌 Future Improvements
- Tune hyperparameters for better learning.(in the .yaml file, keep atleast 500000 steps for learning of the agent.)
- Introduce more complex defender behaviors.

## 📜 License
This project is open-source under the MIT License.

---
👨‍💻 Developed by **[Moulik Tokas]**  
🔗 GitHub: [https://github.com/tennissta99660]  
📫 Contact: [moulik.032006@gmail.com]
