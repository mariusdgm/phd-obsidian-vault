[External Nonparametric Memory in Deep Learning (unsw.edu.au)](https://unsworks.unsw.edu.au/entities/publication/d6d67b37-8382-4326-8926-b925dacd2fdc/full)

[[Atari 100k]]

We propose a method, NAIT, that is purely memory based, but is able to achieve performance comparable with the best neural models on the ATARI100k benchmark. Because NAIT does not make use of parametric function approximation, and instead approximates only locally, it is extremely computationally efficient, reducing the run-time for a full sweep over ATARI100k from days to minutes.

Next, we combine the promising non-parametric retrieval approach of NAIT with large image and text encoders for the task of Long-Tail Visual Recognition. This method, Retrieval Augmented Classification (RAC), achieves state-of-the art performance on the highly competitive long-tail datasets iNaturalist2018 and Places365-LT.

Finally, we move beyond standard single-step retrieval and investigate multi-step retrieval over graphs of sentences for the task of Reading Comprehension. We first propose a mechanism to effectively construct such graphs from collections of documents, and then learn a general traversal policy over such graphs, conditioned on the query. We demonstrate the combination of this retriever with existing models both consistently boosts accuracy and reduces training time by 2-3x.