### Overview

This repository provides code, exercises and solutions for popular Reinforcement Learning algorithms. These are meant to serve as a learning tool to complement the theoretical materials from

- [Reinforcement Learning: An Introduction (2nd Edition)](http://incompleteideas.net/book/RLbook2018.pdf)
- [David Silver's Reinforcement Learning Course](http://www0.cs.ucl.ac.uk/staff/d.silver/web/Teaching.html)

Each folder in corresponds to one or more chapters of the above textbook and/or course. In addition to exercises and solution, each folder also contains a list of learning goals, a brief concept summary, and links to the relevant readings.

All code is written in Python 3 and uses RL environments from [OpenAI Gym](https://gym.openai.com/). Advanced techniques use [Tensorflow](https://www.tensorflow.org/) for neural network implementations.


### Table of Contents

- [Introduction to RL problems & OpenAI Gym](Introduction/)
- [MDPs and Bellman Equations](MDP/)
- [Dynamic Programming: Model-Based RL, Policy Iteration and Value Iteration](DP/)
- [Monte Carlo Model-Free Prediction & Control](MC/)
- [Temporal Difference Model-Free Prediction & Control](TD/)
- [Function Approximation](FA/)
- [Deep Q Learning](DQN/) (WIP)
- [Policy Gradient Methods](PolicyGradient/) (WIP)
- Learning and Planning (WIP)
- Exploration and Exploitation (WIP)


### List of Implemented Algorithms

- [Dynamic Programming Policy Evaluation](DP/Policy%20Evaluation%20Solution.ipynb)
- [Dynamic Programming Policy Iteration](DP/Policy%20Iteration%20Solution.ipynb)
- [Dynamic Programming Value Iteration](DP/Value%20Iteration%20Solution.ipynb)
- [Monte Carlo Prediction](MC/MC%20Prediction%20Solution.ipynb)
- [Monte Carlo Control with Epsilon-Greedy Policies](MC/MC%20Control%20with%20Epsilon-Greedy%20Policies%20Solution.ipynb)
- [Monte Carlo Off-Policy Control with Importance Sampling](MC/Off-Policy%20MC%20Control%20with%20Weighted%20Importance%20Sampling%20Solution.ipynb)
- [SARSA (On Policy TD Learning)](TD/SARSA%20Solution.ipynb)
- [Q-Learning (Off Policy TD Learning)](TD/Q-Learning%20Solution.ipynb)
- [Q-Learning with Linear Function Approximation](FA/Q-Learning%20with%20Value%20Function%20Approximation%20Solution.ipynb)
- [Deep Q-Learning for Atari Games](DQN/Deep%20Q%20Learning%20Solution.ipynb)
- [Double Deep-Q Learning for Atari Games](DQN/Double%20DQN%20Solution.ipynb)
- Deep Q-Learning with Prioritized Experience Replay (WIP)
- [Policy Gradient: REINFORCE with Baseline](PolicyGradient/CliffWalk%20REINFORCE%20with%20Baseline%20Solution.ipynb)
- [Policy Gradient: Actor Critic with Baseline](PolicyGradient/CliffWalk%20Actor%20Critic%20Solution.ipynb)
- [Policy Gradient: Actor Critic with Baseline for Continuous Action Spaces](PolicyGradient/Continuous%20MountainCar%20Actor%20Critic%20Solution.ipynb)
- Deterministic Policy Gradients for Continuous Action Spaces (WIP)
- Deep Deterministic Policy Gradients (DDPG) (WIP)
- [Asynchronous Advantage Actor Critic (A3C)](PolicyGradient/a3c)


### Resources

Books:

- [Reinforcement Learning: An Introduction (2nd Edition)](http://incompleteideas.net/book/RLbook2018.pdf)
- [Algorithms for Reinforcement Learning](https://sites.ualberta.ca/~szepesva/papers/RLAlgsInMDPs.pdf)
- [Bandit Algorithms](https://tor-lattimore.com/downloads/book/book.pdf)

Classes:

- [David Silver's Reinforcement Learning Course (UCL, 2015)](http://www0.cs.ucl.ac.uk/staff/d.silver/web/Teaching.html)
- [CS294 - Deep Reinforcement Learning (Berkeley, Fall 2015)](http://rll.berkeley.edu/deeprlcourse/)
- [CS 8803 - Reinforcement Learning (Georgia Tech)](https://www.udacity.com/course/reinforcement-learning--ud600)
- [CS885 - Reinforcement Learning (UWaterloo), Spring 2018](https://cs.uwaterloo.ca/~ppoupart/teaching/cs885-spring18/)
- [CS294-112 - Deep Reinforcement Learning (UC Berkeley)](http://rail.eecs.berkeley.edu/deeprlcourse/)

Talks/Tutorials:

- [Introduction to Reinforcement Learning (Joelle Pineau @ Deep Learning Summer School 2016)](http://videolectures.net/deeplearning2016_pineau_reinforcement_learning/)
- [Deep Reinforcement Learning (Pieter Abbeel @ Deep Learning Summer School 2016)](http://videolectures.net/deeplearning2016_abbeel_deep_reinforcement/)
- [Deep Reinforcement Learning ICML 2016 Tutorial (David Silver)](http://techtalks.tv/talks/deep-reinforcement-learning/62360/)
- [Tutorial: Introduction to Reinforcement Learning with Function Approximation](https://www.youtube.com/watch?v=ggqnxyjaKe4)
- [John Schulman - Deep Reinforcement Learning (4 Lectures)](https://www.youtube.com/playlist?list=PLjKEIQlKCTZYN3CYBlj8r58SbNorobqcp)
- [Deep Reinforcement Learning Slides @ NIPS 2016](http://people.eecs.berkeley.edu/~pabbeel/nips-tutorial-policy-optimization-Schulman-Abbeel.pdf)
- [OpenAI Spinning Up](https://spinningup.openai.com/en/latest/user/introduction.html)
- [Advanced Deep Learning & Reinforcement Learning (UCL 2018, DeepMind)](https://www.youtube.com/playlist?list=PLqYmG7hTraZDNJre23vqCGIVpfZ_K2RZs)
- [Deep RL Bootcamp](https://sites.google.com/view/deep-rl-bootcamp/lectures)
- [Model-Based Methods in Reinforcement Learning @ ICML2020-Tutorial](https://sites.google.com/view/mbrl-tutorial), [PDF of this tutorial](Talks-and-Tutorials/20200720Model_based%20RL_tutorial.pdf)

Other Projects:

- [carpedm20/deep-rl-tensorflow](https://github.com/carpedm20/deep-rl-tensorflow)
- [matthiasplappert/keras-rl](https://github.com/matthiasplappert/keras-rl)

Selected Papers:

- [Human-Level Control through Deep Reinforcement Learning (2015-02)](http://www.readcube.com/articles/10.1038/nature14236)
- [Deep Reinforcement Learning with Double Q-learning (2015-09)](http://arxiv.org/abs/1509.06461)
- [Continuous control with deep reinforcement learning (2015-09)](https://arxiv.org/abs/1509.02971)
- [Prioritized Experience Replay (2015-11)](http://arxiv.org/abs/1511.05952)
- [Dueling Network Architectures for Deep Reinforcement Learning (2015-11)](http://arxiv.org/abs/1511.06581)
- [Asynchronous Methods for Deep Reinforcement Learning (2016-02)](http://arxiv.org/abs/1602.01783)
- [Deep Reinforcement Learning from Self-Play in Imperfect-Information Games (2016-03)](http://arxiv.org/abs/1603.01121)
- [Mastering the game of Go with deep neural networks and tree search](https://gogameguru.com/i/2016/03/deepmind-mastering-go.pdf)

Solutions for RL competitions:
- KDD Cup 2020 (RL track), Learning to dispatch and reposition on a mobility-on-demand platform [1st solution for task 1: order dispatching](https://github.com/maybeluo/KDDCup2020-RL-1st-solution), and [Details](https://mp.weixin.qq.com/s?__biz=MzA3MzI4MjgzMw==&mid=2650796572&idx=4&sn=9c0bdc189e6567612b222263de977ae3&chksm=871a3662b06dbf743a2b36fb0f77fa149f1077bb0ab84e09574e46966be9610e8455a1a3f476&mpshare=1&scene=1&srcid=0901g4Qr8PqOkS0epQSomtZP&sharer_sharetime=1598937150866&sharer_shareid=1b3376bd3bafcdb7884c34bbd7ffb337&key=bf5b07d1268a5d2054335bb3266b4d25dd70bcf0459fab3d74b918fe0a884ecbf581147d7097444a01120033175ec1c2d4fa95646a2cacc681546b07ee4056690f9abeb06538fdc50f0d37770995ef8936e162397a059943e02d6aad0192ee441fe695d66dbf82a0fdc190b6a08524b987b0a1dd3d783164435ee7315408c1a9&ascene=1&uin=MjE0NzI4MTIwOQ%3D%3D&devicetype=Windows+10+x64&version=62090529&lang=zh_CN&exportkey=AQ3OrxI1c8F8WLv3td1Rz3s%3D&pass_ticket=rpgXEsuHJf%2B6y7DPihn5BU7j7MUeVSGKXfKk5fh%2F9wEas%2BrB%2BhfJz%2Fsw48Vwb2xe).
  Related resources: [Tutorial：Deep Reinforcement Learning with Applications in Transportation](https://outreach.didichuxing.com/internationalconference/kdd2019/tutorial/) at KDD2019

Survey

- No.MARL1:Kaiqing Zhang et al. 2019 [Multi-Agent Reinforcement Learning:A Selective Overview of Theories and Algorithms](https://arxiv.org/pdf/1911.10635.pdf)



