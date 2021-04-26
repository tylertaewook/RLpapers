# RLpapers

This repo lists all the books, papers, and codes I used for my own RL journey.
I will constantly update my progress with my own annotated papers [paper_annot] and code implemented [code] as I continue.
As I'm studying, I will also work on a [RL Jargons List](https://docs.google.com/spreadsheets/d/1TtQPn9n78hDxVIOh44XMBY4sJA3ST4iV2b_Qbw4r5cM/edit#gid=0) for an organized place to list unfamiliar terms.

The papers that are numbered below are part of our curriculum at [DIYA](https://blog.diyaml.com/)'s MultiAgentRL team, where our goal is to read two papers and review them together every week. The other papers are composed to supplement my understandings whenever I have extra time.

### First and foremost, the basics:
- Richard Sutton's [Reinforcement Learning: An Introduction](http://incompleteideas.net/book/the-book.html) 🚧 *2021.04.13-*
- David Silver's [RL Course](https://youtube.com/playlist?list=PLqYmG7hTraZBiG_XpjnPrSNw-1XQaM_gB) 🚧 *2021.04.13-*

### Value Based
1. Playing Atari with Deep Reinforcement Learning, 2013. Algorithm: `DQN` **[[paper_annot]](https://github.com/tylertaewook/RLpapers/blob/main/DQN_annot.pdf) [[code]](https://github.com/tylertaewook/RLpapers/blob/main/DQN.ipynb)** ✅ *2021.04.15*
- Human-level control through deep reinforcement learning, 2015. Algorithm: `DQN` **[[paper]](https://storage.googleapis.com/deepmind-media/dqn/DQNNaturePaper.pdf)**
2. Multiagent Cooperation and Competition with Deep Reinforcement Learning **[[paper]](https://arxiv.org/pdf/1511.08779.pdf)** ✅ *2021.04.15*
3. Deep Recurrent Q-Learning for Partially Observable MDPs, Hausknecht and Stone, 2015. Algorithm: `Deep Recurrent Q-Learning(DRQN)` **[[paper_annot]](https://github.com/tylertaewook/RLpapers/blob/main/DRQN_annot.pdf)** ✅ *2021.04.18*
- Prioritized Experience Replay, Schaul et al, 2015. Algorithm: `Prioritized Experience Replay (PER)` **[[paper]](https://arxiv.org/abs/1511.05952)**
- Dueling **[[paper]](https://arxiv.org/pdf/1511.06581.pdf)**
- Distributional **[[paper]](https://arxiv.org/pdf/1707.06887.pdf)**
- Rainbow **[[paper]](https://arxiv.org/abs/1710.02298)**
- Quantile Regression **[[paper]](https://arxiv.org/abs/1710.10044)**

### DPG
- Deterministic Policy Gradient Algorithms `DPG` **[[paper]](http://proceedings.mlr.press/v32/silver14.pdf)** 
4. Continuous Control With Deep Reinforcement Learning, Lillicrap et al, 2015. Algorithm: `DDPG` **[[paper]](https://github.com/tylertaewook/RLpapers/blob/main/DDPG_annot.pdf)** ✅ *2021.04.18*
5. Multi-Agent Actor-Critic for Mixed Cooperative-Competitive Environments, Lowe et al. 2017. Algorithm: `MADDPG` **[[paper]](https://arxiv.org/abs/1706.02275)**
- Addressing Function Approximation Error in Actor-Critic Methods **[[paper]](https://arxiv.org/pdf/1802.09477.pdf)** ✅ *2021.04.25*

### Policy Gradient
6. Trust Region Policy Optimization, Schulman et al, 2015. Algorithm: `TRPO` ✅ *2021.04.25*
7. High-Dimensional Continuous Control Using Generalized Advantage Estimation, Schulman et al, 2015. Algorithm: `GAE`
8. Proximal Policy Optimization Algorithms, Schulman et al, 2017. Algorithm: `PPO-Clip, PPO-Penalty`
9. Emergence complexity via Muti-agent competition, Bansal et al, 2017.
10. Adversarial Policies: Attacking Deep Reinforcement Learning https://arxiv.org/pdf/1905.10615.pdf

### MARL
11. Counterfactual Multi-Agent Policy Gradient, Foerster et al. Algorithm: `COMA`
12. Monotonic Value Function Factorisation for Deep Multi-Agent Reinforcement Learning, Rashid et al. 2018. Algorithm: `QMIX`
13. Autocurricula and the Emergence of Innovation from Social Interaction: A Manifesto for Multi-Agent Intelligence Research
14. Deep Reinforcement Learning from Self-Play in Imperfect-Information Games NFSP (Neural Fictitious Self-Play)
15. Jaderberg et al. Human-level performance in 3D multiplayer games with population based reinforcement learning https://science.sciencemag.org/content/sci/364/6443/859.full.pdf
16. ASYMMETRIC SELF-PLAY FOR AUTOMATIC GOAL DISCOVERY IN ROBOTIC MANIPULATION Asymmetric self-play & HRL
17. A Unified Game-Theoretic Approach to Multiagent Reinforcement Learning PSRO/DCH

### A2C/A3C
- Asynchronous Methods for Deep Reinforcement Learning **[[paper]](https://arxiv.org/pdf/1602.01783.pdf) [[code]]()**

### SAC
- Soft Actor-Critic: Off-Policy Maximum Entropy Deep Reinforcement Learning with a Stochastic Actor, 2018 **[[paper]](https://arxiv.org/abs/1801.01290)**
- Soft Actor-Critic Algorithms and Applications, 2019 **[[paper]](https://arxiv.org/abs/1801.01290)**
 
### Survey
- Multi-Agent Reinforcement Learning: A Selective Overview of Theories and Algorithms **[[paper]](https://arxiv.org/pdf/1911.10635.pdf)**
- A Survey and Critique of Multiagent Deep Reinforcement Learning **[[paper]](https://arxiv.org/pdf/1810.05587.pdf)**



