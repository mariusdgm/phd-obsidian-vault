[Regioned Episodic Reinforcement Learning | Semantic Scholar](https://www.semanticscholar.org/paper/Regioned-Episodic-Reinforcement-Learning-Jin-Chen/d51fe299b77deb1907216fc1fec3924848f83c31)

Regioned Episodic Reinforcement Learning (RERL)

[[Neural Episodic Control]]
[[Continuous control with deep reinforcement learning]]
[[Proximal Policy Optimization Algorithms]]

Goal-oriented reinforcement learning algorithms are often good at exploration, not exploitation, while episodic algorithms excel at exploitation, not exploration. As a result, neither of these approaches alone can lead to a sample-efficient algorithm in complex environments with high dimensional state space and delayed rewards. 

Motivated by these observations and shortcomings, in this paper, we introduce Regioned Episodic Reinforcement Learning (RERL) that combines the episodic and goal-oriented learning strengths and leads to a more sample efficient and effective algorithm. 

RERL achieves this by decomposing the space into several sub-space regions and constructing regions that lead to more effective exploration and high values trajectories. Extensive experiments on various benchmark tasks show that RERL outperforms existing methods in terms of sample efficiency and final rewards.