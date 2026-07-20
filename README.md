# Reinforcement Learning Policy Optimization for Autonomous Maze Navigation

This repository documents my work during a robotics hackathon, where my team developed and improved a Reinforcement Learning (RL) policy for autonomous robot navigation in a simulated maze environment.

The simulator and environment were provided by the organizers (HCMUT-Faculty of CSE). My contribution focused on improving the agent's decision-making policy through reward engineering, experimentation, and performance analysis.

---

## Project Overview

Objective:
Develop an RL policy capable of navigating an autonomous robot through randomly generated maze environments while maximizing navigation efficiency.

The environment included:

- Randomly generated mazes
- Obstacles and collisions
- Checkpoints
- Goal location
- Reward-based reinforcement learning

---

## My Contributions

- Designed and refined the reward policy
- Tuned reward values through multiple experiments
- Evaluated policy performance on 500+ generated maps
- Analyzed navigation behaviour
- Prepared the final technical presentation
- Presented experimental findings

---

## Reward Design

Example reward configuration:

Goal                +400

Checkpoint          +100

Collision           -200

Action Cost         -2

The reward policy was iteratively improved to balance:

- shortest path
- exploration
- collision avoidance
- stability

---

## Experiments

Different reward strategies were evaluated by comparing:

- success rate
- path efficiency
- collision frequency
- convergence behaviour

The final policy demonstrated significantly more stable navigation behaviour across over 500 generated maps.

---

## Results

- Successfully evaluated on 500+ generated maps
- Improved navigation stability
- Reduced unnecessary exploration
- Better balance between exploration and exploitation

---

## Lessons Learned

This project strengthened my understanding of:

- Reinforcement Learning
- Reward Engineering
- Policy Optimization
- Experimental Design
- Robotics Navigation
- Engineering Teamwork

---

## Note

The simulator, training environment and datasets were provided exclusively for the hackathon and are not publicly available.

Therefore, this repository documents the engineering process and methodology rather than the original source code.
