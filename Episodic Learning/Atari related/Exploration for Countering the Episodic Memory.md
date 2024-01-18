[[PDF] Exploration for Countering the Episodic Memory | Semantic Scholar](https://www.semanticscholar.org/paper/Exploration-for-Countering-the-Episodic-Memory-Zhou-Wang/daa0b9b5f9aba3b87b47429b2a2224eaf7f789b1)

Reinforcement learning is a prominent computational approach for goal-directed learning and decision making, and exploration plays an important role in improving the agent's performance in reinforcement learning. 

In low-dimensional Markov decision processes, table reinforcement learning incorporated within count-based exploration works well for states of the Markov decision processes that can be easily exhausted. It is generally accepted that count-based exploration strategies turn inefficient when applied to high-dimensional Markov decision processes (generally high-dimensional state spaces, continuous action spaces, or both) since most states occur only once in deep reinforcement learning.

Exploration methods widely applied in deep reinforcement learning rely on heuristic intrinsic motivation to explore unseen states or unreached parts of one state. The episodic memory module simulates the performance of hippocampus in human brain. This is exactly the memory of past experience. It seems logical to use episodic memory to count the situations encountered. Therefore, we use the contextual memory module to remember the states that the agent has encountered, as a count of states, and the purpose of exploration is to reduce the probability of encountering these states again. 

The purpose of exploration is to counter the episodic memory. In this article, we try to take advantage of the episodic memory module to estimate the number of states experienced, so as to counter the episodic memory. We conducted experiments on the OpenAI platform and found that counting accuracy of state is higher than that of the CTS model. At the same time, this method is used in high-dimensional object detection and tracking, also achieving good results.

Episodic memory can be used for episodic control and can  
achieve good results in some RL application situations. In the  
case of relatively easy exploration or nonsparse reward, the  
agent can find the path of high reward very smoothly, even  
when reward is sparse. The problems of reward and hard  
exploration are dependent more on the strategy of exploration.  
In this article, we modified the episodic memory module to  
pseudocount state, so as to realize a pseudocount-based ex-  
ploration strategy. The experiment shows that our algorithm  
can achieve good results in OpenAI games as well as computer  
vision applications such as object detection and object  
tracking. In the next step, we plan to expand the counter  
episodic memory to continuous episodic control. Dual net-  
works seem to be a feasible solution, because their inputs are  
all the states at certain time, and their embeddings are  
consistent.