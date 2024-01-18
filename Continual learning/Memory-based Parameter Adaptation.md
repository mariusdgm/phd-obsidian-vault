[[PDF] Memory-based Parameter Adaptation | Semantic Scholar](https://www.semanticscholar.org/paper/Memory-based-Parameter-Adaptation-Sprechmann-Jayakumar/0be49527df4869a0132f5cbc8d4cfa3304ab5843)

Deep neural networks have excelled on a wide range of problems, from vision to language and game playing. Neural networks very gradually incorporate information into weights as they process data, requiring very low learning rates. 

If the training distribution shifts, the network is slow to adapt, and when it does adapt, it typically performs badly on the training distribution before the shift. Our method, Memory-based Parameter Adaptation, stores examples in memory and then uses a context-based lookup to directly modify the weights of a neural network. Much higher learning rates can be used for this local adaptation, reneging the need for many iterations over similar data before good predictions can be made. 

As our method is memory-based, it alleviates several shortcomings of neural networks, such as catastrophic forgetting, fast, stable acquisition of new knowledge, learning with an imbalanced class labels, and fast learning during evaluation. We demonstrate this on a range of supervised tasks: large-scale image classification and language modelling.

A key component of MbPA is the non-parametric, episodic memory. Many recent works have looked at augmenting neural network systems with memories to allow for fast adaptation or incorporation of new knowledge. Variants of this architecture have been successfully used in the context of classification (Vinyals et al., 2016; Santoro et al., 2016; Kaiser et al., 2017), language modelling (Merity  et al., 2016; Grave et al., 2016), reinforcement learning (Blundell et al., 2016; Pritzel et al., 2017),  machine translation (Bahdanau et al., 2014), and question answering (Weston et al., 2014), to name  
a few. 

Directily compares with NEC For the MbPA experiments below, we use a memory architecture similar to the Differentiable  Neural Dictionary (DND) used in Neural Episodic Control (NEC) (Pritzel et al., 2017). One key  difference is that we do not train the embedding network through the gradients from the memories  (as they are not used at training time).  

Our experiments show that MbPA improves performance in continual learning experiments, comparable to or in many cases exceeding the performance of EWC.