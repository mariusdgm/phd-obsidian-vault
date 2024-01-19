[[PDF] Sample-Efficient Reinforcement Learning with Maximum Entropy Mellowmax Episodic Control | Semantic Scholar](https://www.semanticscholar.org/paper/Sample-Efficient-Reinforcement-Learning-with-Sarrico-Arulkumaran/d8bd56621f695b997a036553913368fee7b9ca57)

[[Continuous control with deep reinforcement learning]]
[[Neural Episodic Control]]

Maximum Entropy Mellowmax Episodic Control (MEMEC)

Method consists in new exploration strategy

Baseline is D3QN

Deep networks have enabled reinforcement learning to scale to more complex and challenging domains, but these methods typically require large quantities of training data. 

An alternative is to use sample-efficient episodic control methods: neuro-inspired algorithms which use non-/semi-parametric models that predict values based on storing and retrieving previously experienced transitions. One way to further improve the sample efficiency of these approaches is to use more principled exploration strategies. 

In this work, we therefore propose maximum entropy mellowmax episodic control (MEMEC), which samples actions according to a Boltzmann policy with a state-dependent temperature. We demonstrate that MEMEC outperforms other uncertainty- and softmax-based exploration methods on classic reinforcement learning environments and Atari games, achieving both more rapid learning and higher final rewards.