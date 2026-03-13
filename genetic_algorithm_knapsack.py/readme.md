# Genetic Algorithm – Knapsack Optimization

**Description**
Implementation of a Genetic Algorithm (GA) to solve the Knapsack Problem, aiming to maximize the total value of selected items while respecting a weight capacity constraint. Includes a practice example for string optimization (secret word guessing).

---

## Features

* **Genetic Algorithm Phases**:

  1. Initialization – random population generation
  2. Fitness Evaluation – value maximization with weight penalty
  3. Selection – tournament selection for parent choice
  4. Crossover – one-point crossover to create offspring
  5. Mutation – random bit flips to maintain diversity
  6. Replacement – update population with new offspring
  7. Termination – after max generations or satisfactory solution

* **Supports**:

  * Custom population size and mutation probability
  * Binary representation of solutions
  * Fitness-based selection and convergence analysis

---

## Knapsack Problem Example

| Item | Value | Weight (kg) |
| ---- | ----- | ----------- |
| N1   | 14    | 1           |
| N2   | 23    | 3           |
| N3   | 8     | 7           |
| N4   | 9     | 4           |
| N5   | 17    | 5           |
| N6   | 15    | 6           |

* **Objective:** Maximize total value ≤ 10 kg

---
