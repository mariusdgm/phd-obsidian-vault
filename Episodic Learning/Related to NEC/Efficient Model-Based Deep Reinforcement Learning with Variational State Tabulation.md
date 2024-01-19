[[PDF] Efficient Model-Based Deep Reinforcement Learning with Variational State Tabulation | Semantic Scholar](https://www.semanticscholar.org/paper/Efficient-Model-Based-Deep-Reinforcement-Learning-Corneil-Gerstner/5572169a9adeedb99a6c20f0ede09b320d3fec61)

[[Model-based reinforcement learning and navigation in animals and machines]]

Modern reinforcement learning algorithms reach super-human performance in many board and video games, but they are sample inefficient, i.e. they typically require significantly more playing experience than humans to reach an equal performance level. 

To improve sample efficiency, an agent may build a model of the environment and use planning methods to update its policy. In this article we introduce VaST (Variational State Tabulation), which maps an environment with a high-dimensional state space (e.g. the space of visual inputs) to an abstract tabular environment. 

Prioritized sweeping with small backups, a highly efficient planning method, can then be used to update state-action values. We show how VaST can rapidly learn to maximize reward in tasks like 3D navigation and efficiently adapt to sudden changes in rewards or transition probabilities.

Compares to NEC, trains on Pong