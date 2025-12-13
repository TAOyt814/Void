# DRL-Based 3D Collision Avoidance for Dynamic Environments

This repository provides supplementary materials for our paper on **3D dynamic obstacle avoidance** using deep reinforcement learning (DRL) integrated with the velocity obstacle (VO) method.

## 📁 Included Files

- [`framework.pdf`](./framework.pdf):  
  The overall framework of our proposed method, including perception, planning, and control modules.

- [`real_world_experiments.pdf`](./real_world_experiments.pdf):  
  Results and setup details of real-world experiments, demonstrating the practical deployment of our system.

- [`video.mp4`](./video.mp4):  
  A demonstration video showcasing the agent's behavior in both simulation and real-world scenarios.

---

## ⚙️ Unity ML-Agents Configuration

Our simulation environment is built on the [Unity ML-Agents Toolkit](https://github.com/Unity-Technologies/ml-agents). Below are the key configuration details:

- **Unity Version**: `2021.3.x` *(please match your installed Unity version)*
- **ML-Agents Version**: `v0.29.0` or compatible
- **Environment Name**: `3D-VO-Navigation`
- **Features**:
  - Simulated UGV navigating toward a goal
  - 3D dynamic obstacles (e.g., bouncing balls)
  - Static obstacles represented using 2D grid maps
  - Collision detection and reward feedback

> 📌 Please follow the [official ML-Agents installation guide](https://github.com/Unity-Technologies/ml-agents/blob/main/docs/Installation.md) to set up your Python environment and Unity project.

---

## 🚀 Code Release Plan

We plan to release the core implementation (including training scripts, network structure, and evaluation pipeline) **upon acceptance of the paper**. This will ensure the released code is clean, well-documented, and easy to reproduce.

Stay tuned!

---

## 📬 Contact

For questions, suggestions, or collaborations, feel free to open an issue in this repository or contact the authors directly.

---

Thank you for your interest in our work!

