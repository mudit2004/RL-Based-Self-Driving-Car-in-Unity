# RL-Based-Self-Driving-Car-in-Unity
This project implements a reinforcement learning-based **autonomous driving agent** using **PPO** and **SAC** in a simulated 3D environment.

---

## 🧠 Overview

The goal was to train a driving agent capable of **safe navigation**, **obstacle avoidance**, and **lane discipline** using a custom reward system and Unity ML-Agents.

---

## 🔧 Key Features

- **Algorithms Used:**
  - Proximal Policy Optimization (**PPO**)
  - Soft Actor-Critic (**SAC**)

- **Training Efficiency:**
  - Achieved a **training time of 22 minutes** with SAC compared to **1 hour 21 minutes** with PPO.

- **Reward Engineering:**
  - Designed **invisible checkpoints** to encourage smoother navigation, collision avoidance, and staying within lane boundaries.

- **Perception:**
  - Used Unity’s **RayPerceptionSensorComponent3D** to simulate realistic **3D sensor data** input.

- **Generalization:**
  - Trained on **two distinct tracks** to improve **policy robustness** and reduce overfitting.

---

## 📦 Tools & Frameworks

- Unity ML-Agents  
- Python (for training scripts)  
- Unity (environment setup)  
- PyTorch (underlying ML framework)  

---

## 🏁 Results

| Method | Training Time | Generalization Accuracy |
|--------|----------------|--------------------------|
| PPO    | 1h 21m         | Moderate                 |
| SAC    | **22m**        | High                     |

---

## 📸 Demo

🎥 [Watch the simulation video](#) *(replace this with actual link)*

---

## Code Access

The code for this project is **private**.  
To request access, please contact me:

- 📧 Email: golchhamudit2203@gmail.com  
- 🔗 LinkedIn: [Your LinkedIn Profile](https://www.linkedin.com/in/muditgolchha/)
