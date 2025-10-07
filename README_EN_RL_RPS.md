# 🧠 RL Agent Training for Rock–Paper–Scissors

## 🎯 Task
The goal of this project is to train a reinforcement learning (RL) agent to play the classic **Rock–Paper–Scissors** game against an opponent.
The agent learns through trial and error, improving its decision-making strategy based on the outcomes of previous rounds.

## ⚙️ Technologies Used
- **Python 3.x**
- **NumPy** — for numerical operations
- **Matplotlib** — for visualizing training progress
- **Reinforcement Learning algorithms** — basic Q-Learning implementation
- **Google Colab** — the entire project was developed and tested in Colab

## 🚀 Project Description
This project demonstrates the process of **training an intelligent agent** to play a simple competitive game without any prior knowledge of the rules’ optimal strategy.

The environment consists of three possible actions:
- `Rock`
- `Paper`
- `Scissors`

The agent interacts with the environment, receives a reward for wins (+1), a penalty for losses (−1), and no reward for draws (0).
Through iterative learning (Q-Learning), the agent gradually discovers the best responses to maximize its win rate.

## 🧩 Training Process
1. **Initialize** Q-table for storing state–action values.
2. **Play multiple rounds** between the agent and the opponent.
3. **Update Q-values** based on received rewards.
4. **Balance exploration and exploitation** using ε-greedy policy.
5. **Visualize** the learning curve over time.

## 📊 Results
After several thousand iterations, the agent demonstrates improved strategy and begins to outperform random opponents.
The training visualization shows a steady increase in average reward, confirming that the RL model successfully learned from experience.

## 💡 Key Insights
- Even a simple game like Rock–Paper–Scissors can serve as a great entry point to understanding **reinforcement learning concepts**.
- The project demonstrates the **interaction loop between an agent and environment**, **reward optimization**, and **policy improvement**.

## 🧰 How to Run
The project runs entirely in **Google Colab** — no installation required.
1. Open the notebook file: `RL_Agent_Training_for_Rock–Paper–Scissors.ipynb`
2. Run all cells sequentially.
3. Observe training dynamics and agent performance in real time.

## 👨‍💻 Author
**Aqvafor**
- Email: xaqvaforx@gmail.com
