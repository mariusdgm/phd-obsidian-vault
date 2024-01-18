[[PDF] Generative Temporal Models with Spatial Memory for Partially Observed Environments | Semantic Scholar](https://www.semanticscholar.org/paper/Generative-Temporal-Models-with-Spatial-Memory-for-Fraccaro-Rezende/1c44b632bcd6494f4cfc41c70ed53d93f72473cc)

In model-based reinforcement learning, generative and temporal models of environments can be leveraged to boost agent performance, either by tuning the agent's representations during training or via use as part of an explicit planning mechanism. However, their application in practice has been limited to simplistic environments, due to the difficulty of training such models in larger, potentially partially-observed and 3D environments. 

In this work we introduce a novel action-conditioned generative model of such challenging environments. The model features a non-parametric spatial memory system in which we store learned, disentangled representations of the environment. Low-dimensional spatial updates are computed using a state-space model that makes use of knowledge on the prior dynamics of the moving agent, and high-dimensional visual observations are modelled with a Variational Auto-Encoder. 

The result is a scalable architecture capable of performing coherent predictions over hundreds of time steps across a range of partially observed 2D and 3D environments.


While exploring the environment,  
at each time step we store the position of the agent and  
the corresponding visual information in a Differentiable  
Neural Dictionary (DND) (Pritzel et al., 2017), a scalable  
non-parametric memory developed for episodic control.