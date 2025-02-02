# **Reinforcement Learning on Frozen Lake with Q-Learning**
This project implements **Reinforcement Learning (RL)** to train an agent on the **FrozenLake-v1 environment** using **Gymnasium (Gym)**.

## **👉 Project Overview**
- Trains an RL agent using **Q-Learning**.
- Uses **Gymnasium's FrozenLake-v1** environment.
- Explores different **learning rates, discount factors, and exploration strategies**.
- Evaluates **agent performance in a discrete action space**.

## **🌍 Environment: FrozenLake-v1**
- **Objective:** Navigate a frozen lake without falling into holes.
- **Actions:** Move **Left, Right, Up, Down**.
- **State Space:** Grid-based environment (`5x5`, `8x8`, or `10x10` maps).
- **Probability:** Slippery or deterministic movement.

## **🛠 How to Run**
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/Reinforcement-Learning-FrozenLake.git
   ```
2. **Navigate to the project**:
   ```bash
   cd Reinforcement-Learning-FrozenLake
   ```
3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
4. **Train the RL agent**:
   ```bash
   python train_agent.py
   ```

## **📈 Results**
- Compares performance of different RL parameter settings.
- Demonstrates **how reinforcement learning adapts to different environments**.

## **🗒 Future Improvements**
- Implement **Deep Q-Networks (DQN)** for function approximation.
- Add **policy-based RL methods (REINFORCE, PPO, A2C)**.
- Extend to **more complex RL environments**.

## **🌟 License**
This project is open-source under the **MIT License**.

