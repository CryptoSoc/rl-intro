# Reinforcement Learning Intro

These educational materials originate from the [OpenAI 2018 Hackathon](https://blog.openai.com/hackathon-follow-up/).

This repo contains slides and code for a 30-minute "drink from the firehose" intro to RL, given at the OpenAI Hackthon on March 3rd, 2018. The slides contain a mathemiatical and programming introduction to reinforcement learning from the context of deep neural networks.

The file `pg_cartpole.py` contains an 80-line, bare-bones implementation of policy gradient which seems to work in CartPole. 

The file `dqn_cartpole.py` contains a short but somewhat messy implementation of DQN, which was developed during a Deep Q-Learning workshope at the Hackathon. Cheers to the participants of the workshop, who successfully debugged it!

# Run the Samples

The samples require the python packages `gym`, `tensorflow` and `numpy`.

```bash
pip install tensorflow numpy gym
python pg_cartpole.py
python dqn_cartpole.py
```

Gym may require additional dependencies for a full installation. See here: https://github.com/openai/gym#installation
