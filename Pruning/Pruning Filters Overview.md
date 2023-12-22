[(PDF) Pruning Filters for Efficient ConvNets (2016) | Hao Li | 1050 Citations (typeset.io)](https://typeset.io/papers/pruning-filters-for-efficient-convnets-4hri7wvcp6)

The paper discusses various previous works related to reducing the computation and parameter storage costs of Convolutional Neural Networks (CNNs). Some of the previous works mentioned in the paper are:

- Optimal Brain Damage: a method that prunes weights with a theoretically justified saliency measure.
- Optimal Brain Surgeon: a method that removes unimportant weights determined by the second-order derivative information.
- Mariet & Sra's method: a method that reduces network redundancy by identifying a subset of diverse neurons that do not require retraining. However, this method only operates on the fully-connected layers and introduces sparse connections.
- Approximation methods: past works have proposed to approximate convolutional operations by representing the weight matrix as a low rank product of two smaller matrices without changing the original number of filters. Some of these works include Denil et al., Jaderberg et al., Zhang et al., Tai et al., and Ioannou et al.

The paper proposes a method to reduce the computation costs of CNNs by pruning filters with relatively low weight magnitudes. This method achieves a reduction of about 30% in FLOP for VGGNet and deep ResNets without significant loss in the original accuracy. The authors use a one-shot pruning and retraining strategy for simplicity and ease of implementation. They also perform lesion studies on very deep CNNs to identify layers that are robust or sensitive to pruning, which can be useful for further understanding and improving the architectures.

One limitation of this paper is that the proposed filter pruning method is not compared with other state-of-the-art pruning methods, such as weight pruning or channel pruning. Additionally, the authors only evaluate their method on two datasets, CIFAR-10 and CIFAR-100, and two CNN architectures, VGG-16 and ResNet-110. Therefore, the generalization of the proposed method to other datasets and architectures is not clear. Finally, the paper does not provide a detailed analysis of the computational overheads of the proposed method, such as the time required for filter selection and retraining.