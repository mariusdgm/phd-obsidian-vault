[(PDF) Pruning neural networks without any data by iteratively conserving synaptic flow (2020) | Hidenori Tanaka | 96 Citations (typeset.io)](https://typeset.io/papers/pruning-neural-networks-without-any-data-by-iteratively-39x33auooz)

The contributions of this paper are:

- The paper proposes a novel pruning algorithm called Iterative Synaptic Flow Pruning (SynFlow) that can identify highly sparse trainable subnetworks at initialization without ever training or looking at the data.
- The paper provides a mathematical formulation and experimental verification of a conservation law that explains why existing gradient-based pruning algorithms at initialization suffer from layer-collapse, and how layer-collapse can be entirely avoided.
- The proposed SynFlow algorithm can be interpreted as preserving the total flow of synaptic strengths through the network at initialization subject to a sparsity constraint.
- The SynFlow algorithm consistently competes with or outperforms existing state-of-the-art pruning algorithms at initialization over a range of models, datasets, and sparsity constraints.
- The paper challenges the existing paradigm that, at initialization, data must be used to quantify which synapses are important.

However, the paper does not provide a comparison of the proposed SynFlow algorithm with other state-of-the-art pruning algorithms after training the pruned networks. This limits the ability to draw conclusions about the effectiveness of the proposed algorithm in terms of the final accuracy of the pruned networks. Additionally, the paper does not provide an analysis of the computational cost of the proposed algorithm compared to other state-of-the-art pruning algorithms.