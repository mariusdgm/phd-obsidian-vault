[[PDF] Episodic Memory Deep Q-Networks | Semantic Scholar](https://www.semanticscholar.org/paper/Episodic-Memory-Deep-Q-Networks-Lin-Zhao/06b030f6a7d409e02cedd98321af3a675c011a88)

Reinforcement learning (RL) algorithms have made huge progress in recent years by leveraging the power of deep neural networks (DNN). 

Despite the success, deep RL algorithms are known to be sample inefficient, often requiring many rounds of interactions with the environments to obtain satisfactory performances. Recently, episodic memory based RL has attracted attention due to its ability to latch on good actions quickly. 

In this paper, we present a simple yet effective biologically inspired RL algorithm called Episodic Memory Deep Q-Networks (EMDQN), which leverages episodic memory to supervise an agent during training. Experiments show that our proposed method leads to better sample efficiency and is more likely to find good policy. It only requires 1/5 of the interactions of DQN to achieve many state-of-the-art performances on Atari games, significantly outperforming regular DQN and other episodic memory based RL algorithms.

However, table-based algorithms (e.g. MFEC and NEC)  
lack good generalization, while scalable deep RL methods  
(e.g. DQN, A3C) also have the problem of slow optimization. 

Compared with human brain, which is believed to uti-  
lize both striatum (i.e. reflex) and hippocampus (i.e. mem-  
ory) in decision making [Blundell et al., 2016; Pennartz et  
al., 2011], aforementioned algorithms only rely on a single  
learning system. 

We argue that table-based episodic control  
and DQN are complementary to each other. We can use stria-  
tum to achieve good generalization and use hippocampus to  
accelerate training process via memory module and latch on  
good policy quickly

Experiments on Atari