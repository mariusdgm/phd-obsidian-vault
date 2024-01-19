[[PDF] Addressing Function Approximation Error in Actor-Critic Methods | Semantic Scholar](https://www.semanticscholar.org/paper/Addressing-Function-Approximation-Error-in-Methods-Fujimoto-Hoof/4debb99c0c63bfaa97dd433bc2828e4dac81c48b)

highly cited

Twin Delayed Deep Deterministic policy gradient algorithm (TD3)
Improves DDPG [[Asynchronous Episodic Deep Deterministic Policy Gradient Toward Continuous Control in Computationally Complex Environments]]

In value-based reinforcement learning methods such as deep Q-learning, function approximation errors are known to lead to overestimated value estimates and suboptimal policies. 

We show that this problem persists in an actor-critic setting and propose novel mechanisms to minimize its effects on both the actor and critic. Our algorithm takes the minimum value between a pair of critics to restrict overestimation and delays policy updates to reduce per-update error. 

We evaluate our method on the suite of OpenAI gym tasks, outperforming the state of the art in every environment tested.