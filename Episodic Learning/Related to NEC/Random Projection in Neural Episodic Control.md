[[PDF] Random Projection in Neural Episodic Control | Semantic Scholar](https://www.semanticscholar.org/paper/Random-Projection-in-Neural-Episodic-Control-Nishio-Yamane/fe46b8e91a30814c3813d1a1fe3ddfbaddc5ee3c)
Replaces FC layer with RP projection
Experiments on Atari, outperforms NEC

End-to-end deep reinforcement learning has enabled agents to learn with little preprocessing by humans. However, it is still difficult to learn stably and efficiently because the learning method usually uses a nonlinear function approximation. Neural Episodic Control (NEC), which has been proposed in order to improve sample efficiency, is able to learn stably by estimating action values using a non-parametric method. 

In this paper, we propose an architecture that incorporates random projection into NEC to train with more stability. In addition, we verify the effectiveness of our architecture by Atari's five games. The main idea is to reduce the number of parameters that have to learn by replacing neural networks with random projection in order to reduce dimensions while keeping the learning end-to-end.