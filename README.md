# AI-Search-and-Optimization

This repository is dedicated to exploring the intricacies of search algorithms and optimization techniques within the realm of Artificial Intelligence (AI). It contains implementations of agenda-based and adversarial search strategies, along with a genetic algorithm for password recovery. The goal is to provide a comprehensive suite of AI algorithms that can be used to solve a wide range of problem-solving tasks.

## Table of Contents

- [Introduction](#introduction)
- [Search Algorithms](#search-algorithms)
  - [Agenda-Based Search](#agenda-based-search)
  - [Adversarial Search](#adversarial-search)
- [Genetic Algorithm](#genetic-algorithm)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

AI search algorithms are essential for navigating through complex problem spaces in order to find optimal solutions. This repository demonstrates various search techniques, including depth-first search (DFS), breadth-first search (BFS), uniform cost search (UCS), and best-first search with heuristics. In addition, a genetic algorithm is implemented as an optimization method for finding a target password.

## Search Algorithms

### Agenda-Based Search

This section of the repository covers the implementation and application of various agenda-based search strategies.

- `DFS` - Depth-First Search
- `BFS` - Breadth-First Search
- `UCS` - Uniform Cost Search

Each search algorithm is explained in detail, including their complexities, usage, and specific use-cases.

### Adversarial Search

Focuses on implementing algorithms that are designed to handle decision-making in environments with multiple competing agents.

- `Minimax`
- `Alpha-Beta Pruning`

The adversarial search section demonstrates the algorithms through examples like two-player games where opposing strategies are pitted against each other.

## Genetic Algorithm

A genetic algorithm is used for password recovery by simulating the process of natural selection.

- `Password Recovery` - The process of evolving a population of strings until the target password is obtained.

The genetic algorithm is described in detail, providing insights into the implementation and tuning of hyperparameters.

## Installation

To run the notebook and replicate the findings, ensure you have the following Python packages installed:

```bash
pip install pandas
pip install matplotlib
pip install networkx
