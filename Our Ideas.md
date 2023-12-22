

# 1. Resetting the model and reusing buffer

Figure 2 in [[The Primacy Bias in Deep Reinforcement Learning]] shows an interesting point: keeping the replay buffer from an overtrained experiment leads to a more efficient experiment the second time (The model is completely reset). 

Assumption: the dataset stored in the buffer at the end of the first experiment is higher quality, so the second time the learning is more efficient from the very start. 

Starting from this context, let's discuss the following scenarios:

Consider an environment where the actor can end up in "catastrophic" states (very large negative rewards, compared to the usual rewards provided). These states should be quickly explored and learned to be avoided in the early experiments. Then, the replay buffer eventually cycles out these examples. So what happens if we do the same 2 experiment setting. Will the second experiment end up also discovering these catastrophic examples? Can we avoid this? -> what if we study what is the most efficient way of resetting so that the model is still able to avoid these events. 

Corny quote: "those who forget history are doomed to repeat it."

2 ideas:

### 1. Information encoded in the model
The model encodes information from the early buffer -> identify neurons / structures that encode that information. I expect that maybe those neurons would end up getting reset by redo, even though they were storing a way of avoiding the "catastrophic" event.

### 2. Smart cycling of the buffer 
What if instead of simply cycling the data in the buffer, we would identify what are important samples to keep and not cycle them out? 

- Already done



# 2. Is there a difference in the training performance depending on the shift of the reward distribution?

3 way experiment: 

- balanced rewards (control)
- negative rewards (positive rewards are shifted to be 0 and all the negative rewards are more negative)
- positive rewards (negative rewards are 0)

Does it matter? Will the gradient explode in the unbalanced case? Is there a difference in the number of dead neurons? do we care about the value of the reward, or the difference between expected and observed...