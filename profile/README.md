# 多智能体强化学习课程实验

本组织收录《多智能体强化学习》课程的实验代码与报告，每个实验一个独立仓库。

## 实验列表

| 实验 | 算法 | 环境 | 仓库 |
|---|---|---|---|
| Q-Learning | 表格型 Q-Learning | FrozenLake 8×8 / 12×12 | [q-learning](https://github.com/jubai-coursework/q-learning) |
| DQN | Deep Q-Network | CartPole-v1 | [dqn](https://github.com/jubai-coursework/dqn) |
| PPO 与 DDPG | PPO、DDPG | 连续控制 | [ppo-ddpg](https://github.com/jubai-coursework/ppo-ddpg) |
| 合作型 MARL | IPPO、MADDPG、MAPPO | MPE simple_spread_v3 | [cooperative-marl](https://github.com/jubai-coursework/cooperative-marl) |
| 竞争型 MARL | IPPO、MAPPO | 竞争型多智能体场景 | [competitive-marl](https://github.com/jubai-coursework/competitive-marl) |

## 说明

- 每个仓库都包含完整算法实现、实验报告（`实验报告.md`）与训练结果。
- 训练产物（模型权重、奖励曲线、训练日志）已随仓库提供，可直接查看结果，无需重新训练。
- 各仓库已在 `.gitignore` 中排除课程发放的实验指南 PDF —— 属于教学材料，不随代码公开。

## 技术栈

`Python` · `PyTorch` · `NumPy` · `Matplotlib` · `Gymnasium` · `PettingZoo`
