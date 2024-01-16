[2210.02019.pdf (arxiv.org)](https://arxiv.org/pdf/2210.02019.pdf)

The Arcade Learning Environment (ALE) has become an essential benchmark for assessing the performance of reinforcement learning algorithms. However, the computational cost of generating results on the entire 57-game dataset limits ALE’s use and makes the reproducibility of many results infeasible. We propose a novel solution to this problem in the form of a principled methodology for selecting small but representative subsets of environments within a benchmark suite. We applied our method to identify a subset of five ALE games, called Atari-5, which produces 57-game median score estimates within 10% of their true values. Extending the subset to 10-games recovers 80% of the variance for log-scores for all games within the 57-game set. We show this level of compression is possible due to a high degree of correlation between many of the games in ALE.

In this section, we outline the recommended use of the Atari-5 benchmark, discuss its primary value and limitations, and consider the broader impact of our work. 

We intend Atari-3-Val to be used for hyperparameter tuning and algorithm development and Atari-5 to be used to generate evaluation results. 

In some cases, researchers might want to include results for specific games that demonstrate a strength or weakness of their algorithm while also providing a measure of general performance in the form of Atari-5.

![[Pasted image 20240116211555.png]]

Atari-3 :
Battle Zone, Name This Game, Phoenix 

Atari-5:
Battle Zone, Double Dunk, Name This Game, Phoenix, Q*Bert 

Atari-10:
Amidar, Bowling, Frostbite, Kung Fu Master, River Raid, Battle Zone, Double Dunk, Name This Game, Phoenix, Q*Bert