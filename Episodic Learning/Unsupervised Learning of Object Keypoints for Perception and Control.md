[Unsupervised Learning of Object Keypoints for Perception and Control (neurips.cc)](https://proceedings.neurips.cc/paper_files/paper/2019/file/dae3312c4c6c7000a37ecfb7b0aeb0e4-Paper.pdf)



In summary, our key contributions are: 

• Transporter learns state of the art object keypoints across a variety of commonly used RL environments. Our proposed architecture is robust to varying number, size and motion of objects. 

• Using learned keypoints as state input leads to policies that perform better than state-of-the-art model-free and model-based reinforcement learning methods on several Atari environments, while using only up to 100k ([[Atari 100k]]) environment interactions. 

• Learning skills to manipulate the most controllable keypoints provides an efficient action space for exploration. We demonstrate drastic reductions in the search complexity for exploring challenging Atari environments. Surprisingly, our action space enables random agents to play several Atari games without rewards and any task-dependent learning.