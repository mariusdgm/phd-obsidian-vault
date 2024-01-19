[[PDF] Model-based reinforcement learning and navigation in animals and machines | Semantic Scholar](https://www.semanticscholar.org/paper/Model-based-reinforcement-learning-and-navigation-Corneil/a28e0a7f9ad66dec1e28150bd51954cffe3add42)

[[Efficient Model-Based Deep Reinforcement Learning with Variational State Tabulation]]

A reinforcement learning model that integrates model–based methods and “episodic control”, an approach to reinforcement learning based on episodic memory is described, which learns how to act in the environment by storing snapshot–like memories of its observations and comparing its current observations to similar snapshot memories where it took an action that resulted in high reward.

Only trained on pong 

Compares their VaST with NEC

For decades, neuroscientists and psychologists have observed that animal performance on spatial navigation tasks suggests an internal learned map of the environment. More recently, map-based (or model-based) reinforcement learning has become a highly active research area in machine learning. 

With a learned model of their environment, both animals and artificial agents can generalize between tasks and learn rapidly. In this thesis, I present approaches for developing efficient model--based behaviour in machines and explaining model--based behaviour in animals. From a neuroscience perspective, I focus on the hippocampus, believed to be a major substrate of model-based behaviour in the brain. I consider how hippocampal connectivity enable path--finding between different locations in an environment. 

The model describes how environments with boundaries and barriers can be represented in recurrent neural networks (i.e. attractor networks), and how the transient activity in these networks, after being stimulated with a goal location, could be used for determining a path to the goal. 

I also propose how the connectivity of these map--like networks can be learned from the spatial firing patterns observed in the input pathway to the hippocampus (i.e. grid cells and border cells). From a machine learning perspective, I describe a reinforcement learning model that integrates model-based methods and "episodic control", an approach to reinforcement learning based on episodic memory. 

According to episodic control, the agent learns how to act in the environment by storing snapshot-like memories of its observations, then comparing its current observations to similar snapshot memories where it took an action that resulted in high reward. In our approach, the agent augments these real-world memories with episodes simulated offline using a learned model of the environment. These simulated memories allow the agent to adapt faster when the reward locations change. 

Next, I describe Variational State Tabulation (VaST), a model--based method for learning quickly with continuous and high-dimensional observations (like those found in 3D navigation tasks). The VaST agent learns to map its observations to a limited number of discrete abstract states, and build a transition model over those abstract states. The long--term values of different actions in each state are updated continuously and efficiently in the background as the agent explores the environment. 

I show how the VaST agent can learn faster than other state-of-the-art algorithms, even changing its policy after a single new experience, and how it can respond quickly to changing rewards in complex 3D environments. The models I present allow the agent to rapidly adapt to changing goals and rewards, a key component of intelligence. They use a combination of features attributed to model-based and episodic controllers, suggesting that the division between the two fields is not strict. I therefore also consider the consequences of these findings on theories of model-based learning, episodic control and hippocampal function.