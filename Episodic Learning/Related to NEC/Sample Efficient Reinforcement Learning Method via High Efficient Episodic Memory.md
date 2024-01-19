[[PDF] Sample Efficient Reinforcement Learning Method via High Efficient Episodic Memory | Semantic Scholar](https://www.semanticscholar.org/paper/Sample-Efficient-Reinforcement-Learning-Method-via-Yang-Qin/f715558b65fd4f3c6966505c237d9a622947010b)

[[Episodic Memory Deep Q-Networks]]

Reinforcement Learning (RL), especially Deep Reinforcement Learning (DRL), has made great progress in many areas, such as robots, video games and driving. 

However, sample inefficiency is a big obstacle to the widespread practical application of DRL. Inspired by the decision making in human brain, this problem can be solved by incorporating instance based learning, i.e. episodic memory. 

Many episodic memory based RL algorithms have emerged recently. However, these algorithms either only replace parametric DRL algorithm with episodic control or incorporate episodic memory in a single component of DRL. 

In contrast to preview works, this paper proposes a new sample-efficient reinforcement learning architecture which introduces a new episodic memory module and incorporates episodic thought into some key components of DRL: exploration, experience replay and loss function. 

Taking Deep Q-Network (DQN) algorithm for example, when combined with DQN, our algorithm is called High Efficient Episodic Memory DQN (HE-EMDQN). 

In HE-EMDQN, a new non-parametric episodic memory module is introduced to help calculate the loss and modify the predicted value for exploration. For the sake of accelerating the sample learning in experience replay, an auxiliary small buffer called percentile best episode replay memory is designed to compose a mixed mini-batch. 

We show across the testing environments that our algorithm is significantly more powerful and sample-efficient than DQN and the recent episodic memory deep q-network (EMDQN). This work provides a new perspective for other RL algorithms to improve sample efficiency by utilising episodic memory efficiently.