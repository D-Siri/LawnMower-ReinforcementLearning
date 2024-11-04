# LawnMower-ReinforcementLearning

## Overview

This project implements and compares different reinforcement learning algorithms to solve a lawn mower navigation problem. The goal is to train an agent (lawn mower) to efficiently navigate a 4x4 grid environment and reach a specified goal state while maximizing rewards.

## Environment

- 4x4 grid representing the lawn
- Actions: Up, Down, Right, Left
- Rewards: Up (-5), Down (-6), Right (+5), Left (+6)
- Goal State: (3,3)
- States: Represented as coordinates (i, j) within the grid

## Algorithms Implemented

1. SARSA (State-Action-Reward-State-Action)
2. Double Q-Learning
3. 2-step SARSA 

## Features
- Environment visualization
- Hyperparameter tuning (gamma and epsilon decay)
- Performance comparison between algorithms
- Safety measures to ensure the agent stays within boundaries


## Usage

1. Clone the repository
2. Install the required dependencies
3. Run the main script to train and compare the algorithms
