# awesome-legged-locomotion-learning [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of resources relevant to legged locomotion learning of robotics.



I'm new to the region of legged locomotion, and this awesome list is mainly used to organize and share some source I've seen. This list will be updated gradually.

## Related awesome-lists

- **[awesome-isaac-gym](https://github.com/wangcongrobot/awesome-isaac-gym)**
- [Reinforcement-Learning-in-Robotics](https://github.com/Skylark0924/Reinforcement-Learning-in-Robotics)

## Code

[[legged_gym](https://github.com/leggedrobotics/legged_gym)]: Isaac Gym Environments for Legged Robots ![GitHub stars](https://img.shields.io/github/stars/leggedrobotics/legged_gym.svg?logo=github&label=Stars)

[[FRobs_RL](https://github.com/jmfajardod/frobs_rl)\]: Framework to easily develop robotics Reinforcement Learning tasks using Gazebo and stable-baselines-3. ![GitHub stars](https://img.shields.io/github/stars/jmfajardod/frobs_rl.svg?logo=github&label=Stars)

[[cassie-mujoco-sim](https://github.com/osudrl/cassie-mujoco-sim)]: A simulation library for Agility Robotics' Cassie robot using MuJoCo ![GitHub stars](https://img.shields.io/github/stars/osudrl/cassie-mujoco-sim.svg?logo=github&label=Stars)

[[gym-cassie-run](https://github.com/perrin-isir/gym-cassie-run)]: gym RL environment in which a mujoco simulation of Agility Robotics' Cassie robot is rewarded for walking/running forward as fast as possible. ![GitHub stars](https://img.shields.io/github/stars/perrin-isir/gym-cassie-run.svg?logo=github&label=Stars)

[[apex](https://github.com/osudrl/apex)]: Apex is a small, modular library that contains some implementations of continuous reinforcement learning algorithms. Fully compatible with OpenAI gym. ![GitHub stars](https://img.shields.io/github/stars/osudrl/apex.svg?logo=github&label=Stars)

[[EAGERx](https://github.com/araffin/tools-for-robotic-rl-icra2022)]: Tutorial: Tools for Robotic Reinforcement Learning, Hands-on RL for Robotics with EAGER and Stable-Baselines3. ![GitHub stars](https://img.shields.io/github/stars/araffin/tools-for-robotic-rl-icra2022.svg?logo=github&label=Stars)

## Survey

- A Survey of Sim-to-Real Transfer Techniques Applied to Reinforcement Learning for Bioinspired Robots. (TNNLS, 2021) [**sim2real**] [[paper](https://ieeexplore.ieee.org/abstract/document/9552429)] 
- Robot Learning From Randomized Simulations: A Review. (Frontiers in Robotics and AI, 2022) [**sim2real**] [[paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9038844/pdf/frobt-09-799893.pdf)]
- Sim-to-Real Transfer in Deep Reinforcement Learning for Robotics: a Survey. (IEEE SSCI, 2020) [**sim2real**] [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9308468)]

## Technical blog

- [强化学习环境ISAAC GYM初步入门](https://mp.weixin.qq.com/s?__biz=MzkyNDI5OTA1OA==&mid=2247495740&idx=1&sn=4d06d5ccf9ad9c8a9311bec613833bfd&chksm=c1d54a61f6a2c377769baf47c2fbffd098f091fba392f15802f68ccadb00d94991dcd4d282f4&token=817725460&lang=zh_CN#rd)
- [技术总结《OpenAI Gym》](https://www.meltycriss.com/2018/03/26/tech-gym/)

## Papers

#### Arxiv Preprint

- [2022] NeRF2Real: Sim2real Transfer of Vision-guided Bipedal Motion Skills using Neural Radiance Fields. [[paper](https://arxiv.org/pdf/2210.04932.pdf)]
- [2022] Learning Bipedal Walking On Planned Footsteps For Humanoid Robots. [[paper](https://arxiv.org/pdf/2207.12644.pdf)] [[code](https://github.com/rohanpsingh/LearningHumanoidWalking)]
- [2022] Walking in Narrow Spaces: Safety-critical Locomotion Control for Quadrupedal Robots with Duality-based Optimization. [[paper](https://arxiv.org/pdf/2212.14199.pdf)] [[code](https://github.com/HybridRobotics/quadruped_nmpc_dcbf_duality)]
- [2022] Bridging Model-based Safety and Model-free Reinforcement Learning through System Identification of Low Dimensional Linear Models. [[paper](https://arxiv.org/pdf/2205.05787.pdf)]



### 2023

#### Conference

#### Journal



### 2022

#### Conference

- [**PMLR**] Towards Real Robot Learning in the Wild: A Case Study in Bipedal Locomotion. [[paper](https://proceedings.mlr.press/v164/bloesch22a/bloesch22a.pdf)]
- [**PMLR**] Learning to Walk in Minutes Using Massively Parallel Deep Reinforcement Learning. [**platform**] [[paper](https://proceedings.mlr.press/v164/rudin22a/rudin22a.pdf)] [[code](https://github.com/leggedrobotics/legged_gym)]
- [**CoRL**] Walk These Ways: Tuning Robot Control for Generalization with Multiplicity of Behavior. (Oral) [**control**] [[paper](https://arxiv.org/abs/2212.03238)] [[code](https://github.com/Improbable-AI/walk-these-ways)]
- [**RSS**] Rapid Locomotion via Reinforcement Learning. [[paper](https://github.com/Improbable-AI/rapid-locomotion-rl)] [[code](https://github.com/Improbable-AI/rapid-locomotion-rl)]

#### Journal

- [**IEEE-RAS**] Improving Sample Efficiency of Deep Reinforcement Learning for Bipedal Walking. [[paper](https://ieeexplore.ieee.org/document/10000068)] [[code](https://github.com/rgalljamov/learn2walk)] 
- [**IEEE-RAS**] Dynamic Bipedal Turning through Sim-to-Real Reinforcement Learning. [[paper](https://ieeexplore.ieee.org/abstract/document/10000225)]
- [**TCAS-II**] Parallel Deep Reinforcement Learning Method for Gait Control of Biped Robot .[[paper](https://ieeexplore.ieee.org/document/9690599)]



### 2021

#### Conference

- [**ICRA**] Reinforcement Learning for Robust Parameterized Locomotion Control of Bipedal Robots. [**sim2real**] [[paper](https://ieeexplore.ieee.org/abstract/document/9560769)]

#### Journal



### 2020

#### Conference

- [**RSS**] Learning Memory-Based Control for Human-Scale Bipedal Locomotion. [**sim2real**] [[paper](https://arxiv.org/abs/2006.02402)] [[note](src/notes/Learning_Memory-Based_Control_for_Human-Scale_Bipedal_Locomotion.md)]
- [**IROS**] Crossing the Gap: A Deep Dive into Zero-Shot Sim-to-Real Transfer for Dynamics. [**sim2real**] [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9341617)] [[code](https://github.com/eugval/sim2real_dynamics_simulation)]

#### Journal



### 2019

#### Conference

- [**IROS**] Sim-to-Real Transfer for Biped Locomotion. [[paper](https://ieeexplore.ieee.org/abstract/document/8968053)]

#### Journal



### 2018

#### Conference

- [**IROS**] Feedback Control For Cassie With Deep Reinforcement Learning. [**control**] [[paper](https://ieeexplore.ieee.org/abstract/document/8593722)] [[code](https://github.com/osudrl/cassie-mujoco-sim)] [[note](src/notes/Feedback_Control_For_Cassie_With_Deep_Reinforcement_Learning.md)]
- [**ICRA**] Sim-to-Real Transfer of Robotic Control with Dynamics Randomization. [**sim2real**] [[paper](https://ieeexplore.ieee.org/abstract/document/8460528)] 
- [**RSS**] Sim-to-Real: Learning Agile Locomotion For Quadruped Robots. [**sim2real**] [[paper](http://www.roboticsproceedings.org/rss14/p10.pdf)]

#### Journal

### 2017

#### Conference

- [**ACM SIGGRAPH**] Learning locomotion skills using deeprl: Does the choice of action space matter? [**control**] [[paper](https://xbpeng.github.io/projects/ActionSpace/index.html)] 

#### Journal
