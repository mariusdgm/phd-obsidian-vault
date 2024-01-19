[[PDF] Memory-efficient Reinforcement Learning with Value-based Knowledge Consolidation | Semantic Scholar](https://www.semanticscholar.org/paper/Memory-efficient-Reinforcement-Learning-with-Lan-Pan/5e5ecb65f4b51f9971fe5abcabf1b806411b2ee4)

[[Playing Atari with Deep Reinforcement Learning (DQN)]]

Memory-efficient DQN (MeDQN)

Artificial neural networks are promising for general function approximation but challenging to train on non-independent or non-identically distributed data due to catastrophic forgetting. The experience replay buffer, a standard component in deep reinforcement learning, is often used to reduce forgetting and improve sample efficiency by storing experiences in a large buffer and using them for training later.

However, a large replay buffer results in a heavy memory burden, especially for onboard and edge devices with limited memory capacities. We propose memory-efficient reinforcement learning algorithms based on the deep Q-network algorithm to alleviate this problem. 

Our algorithms reduce forgetting and maintain high sample efficiency by consolidating knowledge from the target Q-network to the current Q-network. Compared to baseline methods, our algorithms achieve comparable or better performance in both feature-based and image-based tasks while easing the burden of large experience replay buffers.

Experiments on Atari