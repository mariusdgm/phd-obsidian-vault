 [Progress & Compress: A scalable framework for continual learning (arxiv.org)](https://arxiv.org/pdf/1805.06370v1.pdf)
 
 Scalable framework for continual learning domains where tasks are learned sequentially
 
 The method involves training a network with two components: a knowledge base capable of solving previously encountered problems and an active column that is employed to efficiently learn the current task. After learning a new task, the active column is distilled into the knowledge base, taking care to protect any previously acquired skills. This cycle of active learning (progression) followed by consolidation (compression) requires no architecture growth, no access to or storing of previous data or tasks, and no task-specific parameters. 

As illustrated in Figure 1, the knowledge base (light blue) is fixed, while the active column (green) is learnt without constraints or regularisation, allowing effective learning on the new task. In addition, P&C enables the reuse of past information through simple layerwise adaptors to the knowledge base (lateral arrows), an idea borrowed from Progressive Nets.

During the “compress” phase, newly learnt behaviour is consolidated into the knowledge base. This is also where methods guarding against catastrophic forgetting are introduced.

As a method of choice for knowledge preservation, we rely on Elastic Weight Consolidation (EWC) (Kirkpatrick et al., 2017), a recently introduced method that poses an approximate Bayesian solution to continual learning. [[Overcoming catastrophic forgetting in neural networks]]

Recently He & Jaeger (2018) proposed a different mechanism, which employs a projection of the gradients such that no direction relevant to the previous task is affected [[Overcoming Catastrophic Interference by Conceptors]]


Comments on [[Gradient Episodic Memory for Continual Learning]]


PLAiD (Berseth et al., 2018) is yet another method that has similarities with our approach. However the method is not designed for continual learning, but rather for maximising transfer, since it assumes access to all tasks at any point in time. The approach relies on two stages, similar to ours. In one stage a new task is learnt, transferring from the previous learnt tasks. In the second stage, the learnt policy is consolidated by multitask distillation from all previously seen tasks. [[Progressive Reinforcement Learning with Distillation for Multi-Skilled Motion Control]]


Identifying task boundaries is significantly easier than identifying task ids, since detection of a change in low level statistics is often sufficient. In the case of reinforcement learning, for example, changes in reward statistics can be used, which intuitively has connections to memory consolidation in the brain due to changes in dopamine levels. 
Another interesting side effect is that the method can, via the γ down-weighting, explicitly forget older tasks in a graceful and controlled (rather than catastrophic) manner. This is useful, for example, if the learning has not converged on an older task, and it is better to gracefully forget its effect on the approximation term. Graceful forgetting is also an important component for continual learning as forgetting older tasks is necessary to make space for learning newer ones, since our model capacity is fixed. Without forgetting, EWC misbehaves when the model runs out of capacity, as discussed in (Kirkpatrick)

Recognition of characters in different alphabets and Atari: “Space Invaders”, “Krull”, “Beamrider”, “Hero”, “Stargunner” and “Ms. Pac-man”

We also evaluate our method on 8 navigation tasks in 3D environments inspired by experiments with Distral (Teh et al., 2017).


 The paper demonstrates the progress & compress approach on sequential classification of handwritten alphabets as well as two reinforcement learning domains: Atari games and 3D maze navigation.

