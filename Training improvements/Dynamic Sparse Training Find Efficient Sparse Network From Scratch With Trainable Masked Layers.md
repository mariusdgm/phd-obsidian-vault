[(PDF) Dynamic Sparse Training: Find Efficient Sparse Network From Scratch With Trainable Masked Layers (2020) | Junjie Liu | 22 Citations (typeset.io)](https://typeset.io/papers/dynamic-sparse-training-find-efficient-sparse-network-from-68xnrgxey8)

This paper presents a new algorithm called Dynamic Sparse Training that can simultaneously find the best network parameters and structure in a single optimization process with trainable pruning thresholds. The main contributions of this paper are:

- Introducing a new algorithm that can train very sparse neural network models with little performance loss using the same training epochs as dense models.
- Demonstrating that Dynamic Sparse Training outperforms state-of-the-art sparse learning algorithms on various network architectures.
- Providing evidence to the effectiveness and efficiency of the algorithm through several surprising observations that reveal the underlying problems of traditional three-stage pruning algorithms and present potential guidance for designing more compact network architectures.

One limitation of this paper is that it mainly focuses on image classification tasks and may not be directly applicable to other types of tasks such as natural language processing or speech recognition. Additionally, the paper does not provide a detailed analysis of the computational cost of the proposed algorithm compared to other pruning methods. Finally, the paper does not explore the impact of different hyperparameters on the performance of the proposed algorithm.