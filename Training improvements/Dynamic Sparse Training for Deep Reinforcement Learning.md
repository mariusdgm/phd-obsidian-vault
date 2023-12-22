[[PDF] Dynamic Sparse Training for Deep Reinforcement Learning | Semantic Scholar](https://www.semanticscholar.org/paper/Dynamic-Sparse-Training-for-Deep-Reinforcement-Sokar-Mocanu/d59324d2534051042ed575e98f656a9e5dfe041c)

Deep reinforcement learning (DRL) agents are trained through trial-and-error interactions with the environment. This leads to a long training time for dense neural networks to achieve good performance. Hence, prohibitive computation and memory resources are consumed. Recently, learning efficient DRL agents has received increasing attention. Yet, current methods focus on accelerating inference time. In this paper, we introduce for the first time a dynamic sparse training approach for deep reinforcement learning to accelerate the training process. The proposed approach trains a sparse neural network from scratch and dynamically adapts its topology to the changing data distribution during training. Experiments on continuous control tasks show that our dynamic sparse agents achieve higher performance than the equivalent dense methods, reduce the parameter count and floating-point operations (FLOPs) by 50%, and have a faster learning speed that enables reaching the performance of dense agents with 40−50% reduction in the training steps.

The paper discusses the need for neural networks that can adapt to changing environmental conditions in the field of deep reinforcement learning. It introduces a dynamic sparse training approach for deep reinforcement learning to accelerate the training process. The proposed approach trains a sparse neural network from scratch and dynamically adapts its topology to the changing data distribution during training. The paper also presents experiments on continuous control tasks to show that the dynamic sparse agents achieve higher performance than the equivalent dense methods, reduce the parameter count and floating-point operations (FLOPs) by 50%, and have a faster learning speed that enables reaching the performance of dense agents with 40-50% reduction in the training steps. The paper also integrates the proposed approach with two state-of-the-art algorithms, TD3 and SAC, to obtain efficient improved versions of these algorithms.

The contributions of this paper are:

- Introducing a dynamic sparse training approach for deep reinforcement learning to accelerate the training process.

- Training a sparse neural network from scratch and dynamically adapting its topology to the changing data distribution during training.

- Achieving higher performance than the equivalent dense methods, reducing the parameter count and floating-point operations (FLOPs) by 50%.

- Having a faster learning speed that enables reaching the performance of dense agents with 40-50% reduction in the training steps.

The main method used in this paper is the proposed dynamic sparse training approach for deep reinforcement learning. This approach trains a sparse neural network from scratch and dynamically adapts its topology to the changing data distribution during training.

One limitation of this paper is that the proposed dynamic sparse training approach may not be suitable for all types of deep reinforcement learning problems. The approach may require some tuning of hyperparameters to achieve optimal performance on different tasks. Additionally, the experiments in the paper were conducted on a limited set of continuous control tasks, and it is unclear how the approach would perform on other types of tasks or in more complex environments.