[[PDF] Model-Based Episodic Memory Induces Dynamic Hybrid Controls | Semantic Scholar](https://www.semanticscholar.org/paper/Model-Based-Episodic-Memory-Induces-Dynamic-Hybrid-Le-Karimpanal/3cdfb3129e8231bb52b09c97921253451ec0ec1d)

Episodic control enables sample efficiency in reinforcement learning by recalling past experiences from an episodic memory. We propose a new model-based episodic memory of trajectories addressing current limitations of episodic control. 

Our memory estimates trajectory values, guiding the agent towards good policies. Built upon the memory, we construct a complementary learning model via a dynamic hybrid control unifying model-based, episodic and habitual learning into a single architecture. 

Experiments demonstrate that our model allows significantly faster and better learning than other strong reinforcement learning agents across a variety of environments including stochastic and non-Markovian settings.

Our contributions are: 
(i) a new model-based control using episodic memory of trajectories; (ii)  a Complementary Learning Systems architecture that addresses limitations of current episodic RL through a dynamic hybrid control unifying model-based, episodic and habitual learning (see Fig. 1);  
(iii) demonstration of our architecture on a diverse test-suite of RL problems from grid-world, classical control to Atari games and 3D navigation tasks. 

We show that the MBEC is noise-tolerant, robust in dynamic grid-world environments. In classical control, we show the advantages of the  
hybrid control when the environment is stochastic, and illustrate how each component plays a crucial role. For high-dimensional problems, our model also achieves superior performance. Further, we interpret model behavior and provide analytical studies to validate our empirical results.