# ❄️ FrozenLake-v1 Reinforcement Learning Agent

A Reinforcement Learning project using the Q-learning algorithm to train an agent to navigate the FrozenLake-v1 environment in OpenAI Gymnasium.  
The agent learns to find the optimal path on an 8x8 randomly generated Frozen Lake map while balancing exploration and exploitation.

---

## 🚀 Features
- Implementation of Q-learning from scratch
- Dynamic 8x8 Frozen Lake environment generation
- Exploration-Exploitation trade-off using Epsilon-Greedy Strategy
- Visualization of rewards over episodes
- Handling slippery surfaces and stochastic transitions

---

## 🎯 Algorithms Used
- **Q-Learning** (Model-Free Reinforcement Learning)

---

## 🛠️ Key Concepts
- State and Action Space Definitions
- Q-Table Initialization and Updates
- Bellman Equation for value updates
- Exploration Rate Decay to shift from exploration to exploitation
- Reward collection and performance tracking

---

## 📈 Training Details
- Episodes: 10,000
- Maximum Steps per Episode: 100
- Learning Rate (α): 0.1
- Discount Rate (γ): 0.99
- Initial Exploration Rate (ε): 1.0
- Minimum Exploration Rate: 0.01
- Exploration Decay Rate: 0.001

---

## 📊 Results
- The agent progressively learned optimal paths over time.
- Reward accumulation trends improved significantly after enough exploration.
- Demonstrated the effectiveness of Q-Learning in discrete, stochastic environments.

---

## 🧑‍💻 Libraries and Tools Used
- Python (NumPy)
- OpenAI Gymnasium (FrozenLake-v1 environment)
- IPython (for cleaner output during training)

---

## 🔥 Future Improvements
- Implement Deep Q-Learning with a Neural Network
- Tune hyperparameters (learning rate, decay rate) further
- Test on custom, larger map sizes (e.g., 10x10 or 12x12 grids)
- Compare Q-Learning performance against SARSA algorithm



---

# ✨ Summary
> Training an agent using Q-learning to master the FrozenLake-v1 environment with dynamic map generation and effective exploration strategies.
