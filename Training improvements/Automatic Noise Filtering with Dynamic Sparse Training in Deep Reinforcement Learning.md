[[PDF] Automatic Noise Filtering with Dynamic Sparse Training in Deep Reinforcement Learning | Semantic Scholar](https://www.semanticscholar.org/paper/Automatic-Noise-Filtering-with-Dynamic-Sparse-in-Grooten-Sokar/4f7dfea2fa810a3cc3fc65bcca52ae2ec1cbe672)

Tomorrow's robots will need to distinguish useful information from noise when performing different tasks. A household robot for instance may continuously receive a plethora of information about the home, but needs to focus on just a small subset to successfully execute its current chore. Filtering distracting inputs that contain irrelevant data has received little attention in the reinforcement learning literature. To start resolving this, we formulate a problem setting in reinforcement learning called the {extremely noisy environment} (ENE), where up to $99\%$ of the input features are pure noise. Agents need to detect which features provide task-relevant information about the state of the environment. Consequently, we propose a new method termed $\textit{Automatic Noise Filtering}$ (ANF), which uses the principles of dynamic sparse training in synergy with various deep reinforcement learning algorithms. The sparse input layer learns to focus its connectivity on task-relevant features, such that ANF-SAC and ANF-TD3 outperform standard SAC and TD3 by a large margin, while using up to $95\%$ fewer weights. Furthermore, we devise a transfer learning setting for ENEs, by permuting all features of the environment after 1M timesteps to simulate the fact that other information sources can become relevant as the world evolves. Again, ANF surpasses the baselines in final performance and sample complexity. Our code is available at [https://github.com/bramgrooten/automatic-noise-filtering](https://github.com/bramgrooten/automatic-noise-filtering)

In this work, we formulated the problem setting of extremely noisy  
environments and showed that our Automatic Noise Filtering algo-  
rithm succeeds at this challenge where standard deep RL methods  
struggle. By using dynamic sparse training, the ANF algorithm  
adjusts its network topology to focus on task-relevant features.