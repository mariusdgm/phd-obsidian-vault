[(PDF) ThiNet: A Filter Level Pruning Method for Deep Neural Network Compression (2017) | Jian-Hao Luo | 1064 Citations (typeset.io)](https://typeset.io/papers/thinet-a-filter-level-pruning-method-for-deep-neural-network-2pimdwofk9)

The contributions of this paper are:

- Proposing a unified framework called ThiNet for pruning unimportant filters in CNN models to simultaneously accelerate and compress the models in both training and test stages with minor performance degradation.
- Establishing a well-defined optimization problem that shows whether a filter can be pruned depends on the outputs of its next layer, not its own layer.
- Comparing the proposed method with other state-of-the-art criteria and showing that it advances the state-of-the-art.
- Demonstrating the effectiveness of the proposed method on ILSVRC-12 benchmark, achieving significant reduction in FLOPs and compression with minor accuracy drop.

The practical implications of this paper are:

- The proposed method can significantly reduce the computational cost and memory footprint of CNN models, making them more efficient for deployment on resource-constrained devices or in real-time applications.
- The proposed method can also speed up the training process of CNN models, which can save time and resources for researchers and practitioners.
- The proposed method can be easily integrated into existing deep learning libraries and frameworks, making it accessible to a wide range of users.
- The proposed method can serve as a starting point for further research on CNN model compression and acceleration, and can inspire the development of more efficient and effective pruning methods.

We formally establish filter pruning as an optimization problem, and reveal that we need to prune filters based on statistics information computed from its next layer, not the current layer, which differentiates ThiNet from existing methods.

Experimental results demonstrate the effectiveness of this strategy, which has advanced the state-of-the-art. We also show the performance of ThiNet on ILSVRC-12 benchmark. ThiNet achieves 3.31 x FLOPs reduction and 16.63× compression on VGG-16, with only 0.52% top-5 accuracy drop. Similar experiments with ResNet-50 reveal that even for a compact network, ThiNet can also reduce more than half of the parameters and FLOPs, at the cost of roughly 1% top-5 accuracy drop. Moreover, the original VGG-16 model can be further pruned into a very small model with only 5.05MB model size, preserving AlexNet level accuracy but showing much stronger generalization ability.

There are a few limitations of this paper, which include:

- The proposed method focuses on filter pruning, which may not be the optimal solution for all types of CNN models or tasks.
- The experiments are mainly conducted on image classification tasks, and the effectiveness of the proposed method on other types of tasks, such as object detection or semantic segmentation, is not fully explored.
- The proposed method may require more computational resources and time for training compared to other simpler pruning methods.
- The paper does not provide a detailed analysis of the impact of pruning on the interpretability of the CNN models.