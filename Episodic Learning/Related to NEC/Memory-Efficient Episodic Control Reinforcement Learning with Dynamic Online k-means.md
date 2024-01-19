[[PDF] Memory-Efficient Episodic Control Reinforcement Learning with Dynamic Online k-means | Semantic Scholar](https://www.semanticscholar.org/paper/Memory-Efficient-Episodic-Control-Reinforcement-Agostinelli-Arulkumaran/fd79c7c5aae1b97f59bab26b5564585109134187)

Dynamic online k-means (DkM), directly compares with MFEC and NEC, proposes a better clustering algo.

Recently, neuro-inspired episodic control (EC) methods have been developed to overcome the data-inefficiency of standard deep reinforcement learning approaches. 

Using non-/semi-parametric models to estimate the value function, they learn rapidly, retrieving cached values from similar past states. In realistic scenarios, with limited resources and noisy data, maintaining meaningful representations in memory is essential to speed up the learning and avoid catastrophic forgetting. 

Unfortunately, EC methods have a large space and time complexity. We investigate different solutions to these problems based on prioritising and ranking stored states, as well as online clustering techniques. We also propose a new dynamic online k-means algorithm that is both computationally-efficient and yields significantly better performance at smaller memory sizes; we validate this approach on classic reinforcement learning environments and Atari games.