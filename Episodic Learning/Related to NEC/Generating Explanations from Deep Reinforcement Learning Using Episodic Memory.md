[[PDF] Generating Explanations from Deep Reinforcement Learning Using Episodic Memory | Semantic Scholar](https://www.semanticscholar.org/paper/Generating-Explanations-from-Deep-Reinforcement-Blakeman-Mareschal/25f7292a7486ea110afff78c375b78e8ac779fbb)

[[Neural Episodic Control]]

Complementary Temporal Difference Learning (CTDL)

Deep Reinforcement Learning (RL) involves the use of Deep Neural Networks (DNNs) to make sequential decisions in order to maximize reward. For many tasks the resulting sequence of actions produced by a Deep RL policy can be long and difficult to understand for humans.

A crucial component of human explanations is selectivity, whereby only key decisions and causes are recounted. Imbuing Deep RL agents with such an ability would make their resulting policies easier to understand from a human perspective and generate a concise set of instructions to aid the learning of future agents. 

To this end we use a Deep RL agent with an episodic memory system to identify and recount key decisions during policy execution. We show that these decisions form a short, human readable explanation that can also be used to speed up the learning of naive Deep RL agents in an algorithm-independent manner.

The fundamental components of CTDL are:
- Deep Neural Network (DNN),  which represents a neocortical learning system 
- Self-Organizing Map (SOM), which represents a hippocampal learning system.

We have proposed a novel method for generating selective task-level explanations from Deep RL agents. The explanations summarize the key-decisions made by the agent as a short temporally ordered list of states, actions and values that can be displayed in a human readable format.

Importantly, the explanations can be used to improve the performance of naive Deep RL agents by simplifying the exploration problem that they face.