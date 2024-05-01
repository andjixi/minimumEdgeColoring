# Minimum Edge Coloring Project

## Overview
Greetings! This project delves into the realm of computational intelligence by tackling the challenging NP-hard problem of achieving the minimum edge coloring in a graph. We've harnessed a diverse range of optimization techniques, including Brute Force, Variable Neighborhood Search (VNS), Simulated Annealing, Particle Swarm Optimization (PSO), Ant Colony Optimization (ACO), and Genetic Algorithm (GA), to navigate this complex problem space.

## Problem Definition

At the heart of our endeavor lies the task of finding the optimal edge coloring in a given graph. This entails assigning colors to edges in such a way that no adjacent edges share the same color, all while striving to minimize the total number of colors used.

- **Instance:** A graph G(V, E) and a set of colors C.
- **Solution:** Color the edges of G such that no two adjacent edges share the same color.
- **Measure:** Minimize the number of colors used in the edge coloring.

## Optimization Techniques
1. **Brute Force:** Exhaustive search algorithm evaluating all possible solutions.
2. **Variable Neighborhood Search (VNS):** Metaheuristic exploring solution space with changing neighborhood structures.
3. **Simulated Annealing:** Probabilistic metaheuristic gradually reducing search space.
4. **Particle Swarm Optimization (PSO):** Population-based stochastic optimization simulating particle movement.
5. **Ant Colony Optimization (ACO):** Population-based metaheuristic using pheromone trails for search guidance.
6. **Genetic Algorithm (GA):** Evolutionary algorithm mimicking natural selection for solution evolution.

## How to Use
1. Clone this repository.
2. Install the required dependencies.
3. Run the desired optimization technique script (e.g., `python vns.py` for Variable Neighborhood Search).
4. Check the output file for results.

## Contributors
- Anđela Jovanović - [@andjixi](https://github.com/andjixi)
- Petra Ignjatović - [@pepi151101](https://github.com/pepi151101)
