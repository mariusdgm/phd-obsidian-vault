[(Open Access) PruneTrain: fast neural network training by dynamic sparse model reconfiguration (2019) | Sangkug Lym | 43 Citations (typeset.io)](https://typeset.io/papers/prunetrain-fast-neural-network-training-by-dynamic-sparse-2ocl3evfke)

This paper proposes a mechanism called PruneTrain that reduces the cost of training convolutional neural networks (CNNs) used in vision applications. The contributions of this paper are:

- Introducing PruneTrain, a cost-efficient mechanism that gradually reduces the training cost during training.
- Using a structured group-lasso regularization approach that drives the training optimization toward both high accuracy and small weight values.
- Periodically removing small weights by reconfiguring the network model to a smaller one.
- Introducing additional reconfiguration techniques to efficiently process the pruned model on a GPU accelerator.
- Achieving a reduction of 39% in the end-to-end training time of ResNet50 for ImageNet by reducing computation cost by 40% in FLOPs, memory accesses by 37% for memory bandwidth bound layers, and the inter-accelerator communication by 55%.

The paper does not provide a comparison of PruneTrain with other state-of-the-art pruning techniques. Additionally, the paper does not explore the impact of PruneTrain on the accuracy of the pruned models. Finally, the paper focuses on ResNet50 for ImageNet dataset, and it is unclear how well PruneTrain would perform on other datasets or architectures.