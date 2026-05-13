# Lab Work: Artificial Intelligence & Expert Systems
**Academic Session:** Fall 2025–2026

## Executive Summary
This portfolio documents the practical implementation of core Artificial Intelligence (AI) principles and Expert System (ES) methodologies. The lab work focused on the mechanical application of search heuristics, agent logic, and optimization algorithms using Python.

---

## 1. Core Programming & Data Architectures
*Ref: Week 01–02*
The semester began with establishing a robust foundation in Python, specifically tailored for AI applications:
* **Dynamic Data Structures:** Implementation of lists as stacks and queues for state-space management.
* **Associative Mapping:** Utilization of dictionaries to represent knowledge bases and graph-based environments.
* **Functional Programming:** Development of modular code for mathematical modeling and iterative logic.

## 2. Intelligent Agents & Environment Simulation
*Ref: Week 03*
Developed and simulated various agent architectures within a controlled environment (Vacuum World):
* **Table-Driven Agents:** Mapping percept sequences to hard-coded action tables.
* **Simple Reflex Agents:** Implementation of condition-action rules for immediate environment response.
* **Model-Based Reflex Agents:** Incorporating internal state tracking to handle partially observable environments and prevent redundant actions.

## 3. Heuristic & Informed Search Algorithms
*Ref: Week 04–05, 07*
Extensive work was conducted on navigating complex state-spaces and solving puzzles:
* **Uninformed Search:** Implementation of **Breadth-First Search (BFS)** and **Depth-First Search (DFS)** for pathfinding on the Romanian Map.
* **Informed Search:** Applied **Uniform Cost Search (UCS)**, **Greedy Best-First Search**, and **A* Search** using custom heuristics (e.g., Straight-line distance to Bucharest).
* **Problem Solvability:** Developed algorithms to calculate **inversion counts** for N-Puzzle configurations to determine mathematical solvability before execution.

## 4. Constraint Satisfaction & Evolutionary Computing
*Ref: Week 06, 08–09*
The final phase focused on optimization and complex constraints:
* **Genetic Algorithms (GA):** Developed a bio-inspired optimization framework to maximize the function $f(x) = x^2 - 11x + 150$. This included binary encoding, roulette wheel selection, crossover, and mutation.
* **Constraint Satisfaction Problems (CSP):** Implemented Map Coloring using heuristics like **Minimum Remaining Values (MRV)** and **Highest Degree Node** to optimize variable assignment.
* **N-Queen Attack Detection:** Designed logic to detect row, column, and diagonal conflicts for $N$-Queen placement, essential for backtracking search algorithms.

---

## Technical Stack
* **Language:** Python 3.x
* **Libraries:** NumPy (Matrix manipulation), PriorityQueue (Search optimization), Random (Stochastic processes).
* **Environments:** Jupyter Notebook / Google Colab.
