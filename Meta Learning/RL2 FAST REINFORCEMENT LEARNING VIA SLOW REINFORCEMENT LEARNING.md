[RL2: Fast Reinforcement Learning via Slow Reinforcement Learning (arxiv.org)](https://arxiv.org/pdf/1611.02779.pdf)

[(2) New Messages! (typeset.io)](https://typeset.io/papers/rl-2-fast-reinforcement-learning-via-slow-reinforcement-159h9yj95g)

- The paper proposes a method called RL^2, which represents a fast reinforcement learning algorithm as a recurrent neural network (RNN) and learns it from data.
- The RNN retains its state across episodes in a given Markov Decision Process (MDP) and stores the state of the "fast" RL algorithm on the current MDP
- This paper suggests a different approach for designing better reinforcement learning algorithms: instead of acting as the designers ourselves, learn the algorithm end-to-end using standard reinforcement learning techniques.
- The paper evaluates RL^2 on a vision-based navigation task implemented using the ViZDoom environment, showing that RL^2 can also scale to high-dimensional problems
- The method is able to represent a fast reinforcement learning algorithm as a recurrent neural network (RNN) and learn it from data.


VISUAL NAVIGATION
The agent is asked to navigate a randomly generated maze to find a randomly placed target2 . The agent receives a +1 reward when it reaches the target, −0.001 when it hits the wall, and −0.04 per time step to encourage it to reach targets faster. 