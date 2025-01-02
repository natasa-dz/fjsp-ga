# Flexible Job Shop Problem (FJSP) Solver

This repository contains a Python implementation of a genetic algorithm to solve the Flexible Job Shop Problem (FJSP). FJSP is a complex scheduling problem that involves allocating operations of various jobs to a set of flexible machines with the goal of minimizing total processing time.

## Features
- **Genetic Algorithm Implementation**: Includes processes like selection, crossover, and mutation to evolve solutions.
- **Customizable Parameters**: Easily adjust population size, mutation rate, and number of generations.
- **Fitness Evaluation**: Measures the quality of schedules based on the total time required.
- **Visualization of Results**: (Optional) Displays the evolution of fitness values over generations.

## Problem Overview
FJSP requires scheduling jobs with multiple operations, each of which can be performed by one or more machines. The goal is to determine:
1. Which machine should handle each operation.
2. The sequence of operations for each machine.

The challenge lies in balancing workload and minimizing the total processing time.

## Getting Started

### Prerequisites
- Python 3.7+
- Required libraries (install with `pip install -r requirements.txt`):
  - `numpy`
  - `matplotlib` (optional, for visualizations)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/fjsp-ga.git
   cd fjsp-ga

### Parameters

- POPULATION_SIZE - Number of individuals in the population.
- GENERATION_SPAN - Number of generations to evolve.
- MUTATION_RATE - Probability of mutation.
- ELITE_RANK - Number of elite individuals to preserve.

### Authors
- Nataša Džudžar
- Uroš Muškinja
