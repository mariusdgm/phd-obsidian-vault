[[PDF] BOOK: Storing Algorithm-Invariant Episodes for Deep Reinforcement Learning | Semantic Scholar](https://www.semanticscholar.org/paper/BOOK%3A-Storing-Algorithm-Invariant-Episodes-for-Deep-Chang-Yoo/3b8473467c22cdeba3f0d45f75455cb9451f9f05)

We introduce a novel method to train agents of reinforcement learning (RL) by sharing knowledge in a way similar to the concept of using a book. The recorded information in the form of a book is the main means by which humans learn knowledge. Nevertheless, the conventional deep RL methods have mainly focused either on experiential learning where the agent learns through interactions with the environment from the start or on imitation learning that tries to mimic the teacher.

Contrary to these, our proposed book learning shares key information among different agents in a book-like manner by delving into the following two characteristic features: (1) By defining the linguistic function, input states can be clustered semantically into a relatively small number of core clusters, which are forwarded to other RL agents in a prescribed manner.
(2) By defining state priorities and the contents for recording, core experiences can be selected and stored in a small container. We call this container as ‘BOOK’. 

Our method learns hundreds to thousand times faster than the conventional methods by learning only a handful of core cluster information, which shows that deep RL agents can effectively learn through the shared knowledge from other agents.

Does experiment on Atari