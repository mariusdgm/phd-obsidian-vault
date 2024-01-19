[[PDF] Solving Continuous Control with Episodic Memory | Semantic Scholar](https://www.semanticscholar.org/paper/Solving-Continuous-Control-with-Episodic-Memory-Kuznetsov-Filchenkov/36f9e864a093c079a1d9e4adab15016027b1ab32)

[[Neural Episodic Control]]

Episodic Memory Actor-Critic (EMAC)
Algorithm based on DDPG [[Continuous control with deep reinforcement learning]]
not atari, continuous problems

Episodic memory lets reinforcement learning algorithms remember and exploit promising experience from the past to improve agent performance. 

Previous works on memory mechanisms show benefits of using episodic-based data structures for discrete action problems in terms of sample-efficiency. The application of episodic memory for continuous control with a large action space is not trivial. 

Our study aims to answer the question: can episodic memory be used to improve agent's performance in continuous control? Our proposed algorithm combines episodic memory with Actor-Critic architecture by modifying critic's objective. We further improve performance by introducing episodic-based replay buffer prioritization. We evaluate our algorithm on OpenAI gym domains and show greater sample-efficiency compared with the state-of-the art model-free off-policy algorithms.