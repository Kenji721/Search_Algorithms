# Search Algorithms

## Overview
This repository contains implementations of various **search algorithms** used in artificial intelligence and optimization problems. Each algorithm is implemented in Python and designed to explore different strategies for searching through problem spaces.

## Algorithms Implemented

### 1. **Branch and Bound (`BranchAndBound.py`)**
   - **Description**: A systematic method for solving optimization problems by breaking them into smaller subproblems (branches) and eliminating (bounding) those that cannot produce better solutions than the current best.

### 2. **Greedy Best-First Search (`GBFS.py`)**
   - **Description**: An informed search algorithm that expands the most promising node (with the lowest heuristic cost) first. It is fast but may not always find the optimal solution.

### 3. **Graph Representation (`Graph.py`)**
   - **Description**: A utility module that represents graphs used in the various search algorithms.

### 4. **Heuristic Functions (`Heuristic.py`)**
   - **Description**: Contains heuristic functions used by informed search algorithms such as A* and Greedy Best-First Search.

### 5. **Main Execution (`Main.py`)**
   - **Description**: The entry point for running and testing different search algorithms on predefined problems.

### 6. **Steepest Hill Climbing (`Steep_Hill.py`)**
   - **Description**: A local search algorithm that always moves towards the steepest ascent (best improvement). It is prone to getting stuck in local optima.

### 7. **Stochastic Hill Climbing (`Stoch_Hill.py`)**
   - **Description**: A variation of hill climbing where the next move is chosen randomly among better moves, reducing the chances of getting stuck in local optima.

### 8. **A* Search (`aStar.py`)**
   - **Description**: A powerful informed search algorithm that uses both the cost to reach a node and a heuristic to estimate the cost to the goal. It guarantees an optimal solution if the heuristic is admissible.

### 9. **Beam Search (`beam.py`)**
   - **Description**: A heuristic search algorithm that keeps only the best `k` states at each level, reducing memory usage compared to A* but potentially missing optimal solutions.

### 10. **Genetic Algorithm (`genetic.py`)**
   - **Description**: An optimization algorithm inspired by natural selection. It evolves candidate solutions over multiple generations to find an optimal or near-optimal solution.

### 11. **Simulated Annealing (`simAnn.py`)**
   - **Description**: A probabilistic optimization algorithm inspired by the annealing process in metallurgy. It allows for occasional moves to worse states to escape local optima.

### 12. **Weighted A* (`wAStar.py`)**
   - **Description**: A variation of A* search where the heuristic is weighted to favor faster solutions over optimality. It trades off optimality for speed.

---

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/search-algorithms.git
   cd search-algorithms
