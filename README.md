# Reinforcement Learning Coursework Solutions

This repository contains solutions to three problem sets from the Reinforcement Learning course. Each solution is detailed in a Jupyter notebook within the `/solutions/` folder. Below is a summary of the problem sets and the concepts applied and learned through their completion.

---

## Problem Set 1: Dynamic Programming

### Overview
This problem set focuses on using dynamic programming methods to solve Markov Decision Processes (MDP) with known transition and reward functions. The scenario involves controlling a queueing system, where the objective is to manage the number of requests in a queue. This set teaches the fundamentals of dynamic programming, including policy evaluation and the calculation of optimal policies using policy iteration and value iteration methods.

### Key Concepts Practiced
- Implementation of lazy and aggressive policies
- Policy evaluation using power iteration or solving Bellman equations
- Optimal policy calculation using policy iteration and value iteration
- Analysis of the performance of policies and convergence properties of the methods

---

## Problem Set 2: Approximate Dynamic Programming

### Overview
This set extends the first by introducing Temporal Difference (TD) and Least Squares Temporal Difference (LSTD) methods for policy evaluation. It explores the use of different feature maps for function approximation, including fine, coarse, and piecewise linear feature maps.

### Key Concepts Practiced
- Approximate policy evaluation using TD(0) and LSTD under various sampling conditions
- Implementation of approximate policy iteration using LSTD for policy evaluation
- Comparison and analysis of value functions and policies under different feature maps

---

## Problem Set 3: Soft Policy Iteration

### Overview
The final problem set investigates the Soft Policy Iteration algorithm, focusing on its convergence properties. This set involves modifying the MDP scenario slightly and implementing the algorithm using the piecewise linear feature map for policy evaluation.

### Key Concepts Practiced
- Implementation of Soft Policy Iteration with a uniform initial policy
- Use of LSTD for policy evaluation in the context of Soft Policy Iteration
- Analysis of the effects of different learning rate parameters on the algorithm's performance
- Comparison of "hard" and "soft" policy iteration methods

---
Each notebook in the `/solutions/` folder provides a detailed implementation, analysis, and discussion of these concepts, showcasing the application of Reinforcement Learning theories to practical problems.
