[[PDF] Neural Episodic Control with State Abstraction | Semantic Scholar](https://www.semanticscholar.org/paper/Neural-Episodic-Control-with-State-Abstraction-Li-Zhu/4875b7cdb20e23c4ada3ef58d48389b0c76052e3)

Neural Episodic Control with State Abstraction (NECSA) 2023

[[Continuous control with deep reinforcement learning]]
[[Addressing Function Approximation Error in Actor-Critic Methods]]
[[Solving Continuous Control with Episodic Memory]]
[[Generalizable Episodic Memory for Deep Reinforcement Learning]]

Compares to DDPG, TD3, EMAC, GEM and outperforms
mujoco and atari

Existing Deep Reinforcement Learning (DRL) algorithms suffer from sample inefficiency. Generally, episodic control-based approaches are solutions that leverage highly-rewarded past experiences to improve sample efficiency of DRL algorithms. 

However, previous episodic control-based approaches fail to utilize the latent information from the historical behaviors (e.g., state transitions, topological similarities, etc.) and lack scalability during DRL training. This work introduces Neural Episodic Control with State Abstraction (NECSA), a simple but effective state abstraction-based episodic control containing a more comprehensive episodic memory, a novel state evaluation, and a multi-step state analysis. 

We evaluate our approach to the MuJoCo and Atari tasks in OpenAI gym domains. The experimental results indicate that NECSA achieves higher sample efficiency than the state-of-the-art episodic control-based approaches.