# Rock-Paper-Scissors Reinforcement Learning Environment

This project simulates a basic **Rock-Paper-Scissors** environment for reinforcement learning experiments. It includes a simple reward function and a rule-based opponent strategy to allow agents to learn and adapt their gameplay over time.

## 📌 Features

- **Action space**: Rock (`R`), Paper (`P`), Scissors (`S`)
- **Reward system**:
  - Win = +1
  - Draw = 0
  - Loss = -1
- **Opponent strategies**:
  - Rule-based: cycles to the next action in the sequence `R → P → S → R`
  - Random: randomly chooses any of the three actions

## 🧠 Core Functions

- `get_reward(agent_move, opponent_move)`: Computes the reward based on standard game rules.
- `opponent_rule_based(prev_move)`: Generates opponent's move based on a fixed deterministic rule.
- `play_round(agent_move, strategy, prev_move)`: Plays one round with the specified strategy (`rule` or `random`).
## Dependencies
- Python standard libraries only (random)

