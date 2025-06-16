# 🧠 A3C Algorithm for Kung Fu Master Environment 🎮

This repository implements the **Asynchronous Advantage Actor-Critic (A3C)** algorithm using PyTorch to train an agent in the **Kung Fu Master** environment from OpenAI Gym (Atari).

---

## 🎯 Objective

Train an AI agent to play and master the *Kung Fu Master* Atari game using A3C — a parallelized reinforcement learning algorithm.

---

## 🧰 Technologies Used

- Python 3
- PyTorch
- OpenAI Gymnasium (`KungFuMaster-v0`)
- A3C (Asynchronous Advantage Actor-Critic)
- Multiprocessing
- Google Colab (for training)

---

## 🏗️ A3C Overview

A3C is a policy gradient method that runs multiple agents in parallel environments. Each agent updates a shared global network asynchronously, which speeds up learning and stabilizes training.

### Core Components:

- **Global Network** (shared weights)
- **Worker Agents** (run in parallel, each with its own environment)
- **Actor-Critic Architecture**
  - Actor: selects actions using the policy
  - Critic: evaluates the value of states

---

