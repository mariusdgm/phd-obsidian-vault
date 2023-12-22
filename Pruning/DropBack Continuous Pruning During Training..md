[(Open Access) DropBack: Continuous Pruning During Training. (2018) | Maximilian Golub | 12 Citations (typeset.io)](https://typeset.io/papers/dropback-continuous-pruning-during-training-121juyjzv8)

This paper introduces a new technique called DropBack that compresses deep neural networks during and after training by only updating the weights with the highest total gradients during backpropagation. The remaining weights are forgotten and their initial value is regenerated at every access to avoid storing them in memory. This technique reduces the number of off-chip memory accesses during both training and inference, which is a key component of the energy needs of DNN accelerators.

The contributions of this paper are:

- Introducing a new technique called DropBack that compresses deep neural networks during and after training by only updating the weights with the highest total gradients during backpropagation.
- Demonstrating that DropBack can achieve high accuracy across network architectures while dramatically reducing the number of off-chip memory accesses during both training and inference.
- Showing that DropBack can achieve weight compression of 25x with LeNet-300-100 on MNIST while maintaining accuracy, and approximately 5x weight compression on 3 models: an already 9x-reduced VGG-16, Densenet, and WRN-28-10 - all with zero or negligible accuracy loss.
- Improving on the state of the art for compressing Densenet and WRN, which are particularly challenging to compress, achieving higher compression with better accuracy than prior pruning techniques.

One limitation of this paper is that it only focuses on weight compression and does not address other aspects of model compression, such as quantization or sparsity. Additionally, the paper does not explore the impact of DropBack on the training time of deep neural networks. Finally, the paper only evaluates the performance of DropBack on a limited set of network architectures and datasets, so its generalizability to other architectures and datasets is not clear.