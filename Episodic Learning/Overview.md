
Model-Free Episodic control (MFEC) maintains a value table and uses k-nearest neighbor to read the values.

Neural Episodic Control (NEC) extends MFEC and uses state-key mapping as a CNN embedding network trained to minimize TD error of memory-based value estimation.

Deep Recurrent Q-Network (DRQN) uses an LSTM for the Q-network in DQN