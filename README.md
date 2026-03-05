# RL Algorithms

This repo contains a set of RL algorithms implemented from first principles. These notebooks help to understand the inner workings of modern RL libraries such as Stable Baselines. Detailed analysis and comparisons are provided inline with the code.

## Algorithms Implemented
### Tabular RL
- [ ] Multi-armed Bandits
- [ ] Value Iteration
- [ ] Policy Iteration
- [x] Monte Carlo
- [x] SARSA
- [x] Q-Learning

### Deep RL
**Model-free**

*Value Function*
- [ ] DQN: Deep Q-Learning
- [ ] Double DQN

*Actor-Critic*
- [ ] DDPG: Deep Deterministic Policy Gradient
- [ ] SAC: Soft Actor-Critic
- [ ] TRPO: Trust Region Policy Optimization
- [ ] PPO: Proximal Policy Optimization

*Policy Gradients*
- [ ] Vanilla Policy Gradient
- [ ] Natural Policy Gradient

**Model-based**
- [ ] World Models

### Multi-agent RL
- [ ] MADDPG: Multi-agent DDPG


## Setup
> This project uses `uv` as the package/environment manager. Install it from [here](https://docs.astral.sh/uv/getting-started/installation/).

```bash
git clone https://github.com/nveshaan/rl_scratch.git
cd rl_scratch
uv sync
```

To update the cloned repo,
```bash
git pull
uv sync
```

## Acknowledgements

Part of the implementation is inspired from https://github.com/NithinVS2k4/RLFromScratch.