# Training Atari Games using Deep Reinforcement Learning

## Overview

Deep Q-Network (DQN) is the first deep reinforcement learning method proposed by DeepMind.

Here we will train a Tensorflow DQN implementation based on [DeepMind's DQN](https://storage.googleapis.com/deepmind-data/assets/papers/DeepMindNature14236Paper.pdf) for playing Atari games.

## Dependencies

- [gym](https://gym.openai.com)
- [Tensorflow](https://www.tensorflow.org)

Either use Virtual Environment through venv or anaconda:

- [virtualenv](https://virtualenv.pypa.io/en/latest/installation.html)
- [Anaconda](https://www.continuum.io/downloads)
 
## Basic Usage

To run, type the following into the terminal

```bat
$ python main.py --game <env_name>
```

However, if you are on an Anaconda virtual environment no need to type <env_name> just type 

```bat
$ python main.py --game SpaceInvaders-v0 --display true
```

and instead of `SpaceInvaders-v0` just type any other game name.

## Acknowledgement

Thank you Kee Hyun Won for inspiring this code. I just adjusted the code for my environment and for the new 
tensorflow deprecated variables.

