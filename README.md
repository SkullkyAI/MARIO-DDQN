# Training of an agent playing Super Mario through RL and CNN

## Introduction

This project is an implementation of a Deep Q-Network (DQN) agent for reinforcement learning tasks. The agent is designed to interact with an environment and learn an optimal policy over time.

## Features

- Customizable hyperparameters: The agent's learning rate, discount factor, epsilon (for epsilon-greedy action selection), epsilon decay rate, minimum epsilon, batch size, and the rate at which the target network is updated can all be customized.
- Replay buffer: The agent uses a replay buffer to store past experiences, which are then sampled in batches to update the network.
- Epsilon-greedy action selection: The agent uses an epsilon-greedy policy for action selection, with epsilon decaying over time to a specified minimum value.

## Usage

The main file is the `MARIO.ipynb` file. 

To use the agent, you can create an instance of the agent with your desired hyperparameters, then call the agent's methods to interact with your environment and update the agent's networks.

## Hyperparameters

- `input_dims`: The dimensions of the input to the neural network.
- `num_actions`: The number of actions the agent can take.
- `lr`: The learning rate for the network updates.
- `gamma`: The discount factor for future rewards.
- `epsilon`: The initial probability of the agent taking a random action.
- `eps_decay`: The rate at which epsilon decays over time.
- `eps_min`: The minimum value to which epsilon can decay.
- `replay_buffer_capacity`: The capacity of the replay buffer.
- `batch_size`: The size of the batches sampled from the replay buffer to update the networks.
- `sync_network_rate`: The number of steps that should pass before the target network is updated to match the main network.


