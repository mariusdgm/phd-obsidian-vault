[(Open Access) Channel Pruning for Accelerating Very Deep Neural Networks (2017) | Yihui He | 1222 Citations (typeset.io)](https://typeset.io/papers/channel-pruning-for-accelerating-very-deep-neural-networks-2pbfa4zu0r)

The paper discusses different methods that have been used to accelerate convolutional neural networks (CNNs). Some of these methods include:

- Optimized implementation: This involves using special convolution algorithms like FFT to accelerate convolution.
- Quantization: This reduces the computational complexity of floating point operations.
- Structured simplification: This involves eliminating connections between neurons to reduce the complexity of the network.

The paper proposes a new method for accelerating very deep CNNs by pruning channels in each layer using a LASSO regression based channel selection and least square reconstruction. The method is effective in reducing the accumulated error and is compatible with various architectures. The pruned VGG-16 achieves state-of-the-art results with a 5x speed-up and only a 0.3% increase in error. The method is also able to accelerate modern networks like ResNet and Xception with only a 1.4% and 1.0% accuracy loss under 2x speedup, respectively.

One limitation of this paper is that the proposed method may not work well for networks with a small number of channels. Additionally, the method may not be suitable for tasks that require high accuracy, as there is still a slight decrease in accuracy when using the pruned networks. Finally, the paper does not explore the impact of pruning on other aspects of the network, such as robustness to adversarial attacks.