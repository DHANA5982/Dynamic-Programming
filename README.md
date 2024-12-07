## Overview
This project involves designing an agent to play Connect X (Connect 4) for the Kaggle online competition. The game uses a 4x5 grid with a 3-in-a-row rule, where two players compete against the default agents: 'random' (easy) and 'negamax' (hard). The project explores various strategies to improve the agent's performance using reinforcement learning techniques.

## Key Features
- **Grid size**: 4x5
- **Win condition**: 3 in a row
- **Players**: Two players (Random Agent and Negamax Agent)
- **Methods Tested**: Random Choice, SARSA, Q-Learning

## Strategies Explored
- Focused on placing pieces 3 in a row to win rather than blocking the opponent.
- Attempted to track and learn from the opponent's actions, especially the 'negamax' agent using its mini-max algorithm.
- Employed learned policies to improve performance, but tracking opponent actions was difficult, impacting the agent's ability to perform well against the 'negamax' agent.

## Learning Techniques
- **Random Choice**: The agent initially made random actions and then switched to learned policies.
- **SARSA**: A reinforcement learning algorithm to update the agent's policy based on current actions and subsequent rewards.
- **Q-Learning**: Another reinforcement learning algorithm that updates the agent's policy based on the maximum future reward.

## Results
- Despite progress, none of the algorithms (Random Choice, SARSA, Q-Learning) performed well against the 'negamax' agent.
- The challenge was primarily in tracking the opponent’s moves effectively, which hindered the performance of the learning models.

## Conclusion
The project provided insights into the challenges of building an effective agent for Connect X, especially against a 'negamax' opponent. The learning methods tested showed improvements over random actions, but further work is needed to refine the agents, especially in tracking and responding to opponent strategies. Future improvements may focus on better tracking of the opponent’s actions and incorporating more advanced reinforcement learning techniques.

