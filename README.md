[Video link](https://www.youtube.com/watch?v=0_oonRc7Sn8) for my talk @pydataberlin

# All that likelihood with PyMC3
The likelihood function is a central concept in Bayesian computation. In this tutorial, we will learn about what is the likelihood function and how do we use it for inference. Using PyMC3, I will demonstrate how to get the likelihood from a model, how does it connect to inference using MCMC sampling or approximation, and some practical usage of the model likelihood to perform model comparisons.

In the past years, we see a growing interested in probabilistic programming and Bayesian statistics. While modern probabilistic library such as PyMC3 and Stan provide flexibility to the user to write down complex model easily, it is not always intuitive how inference is done. More specifically, what is the sampler "seeing"? Learning about likelihood is central to the understanding of how inference is performed. In this tutorial, I would like to give some introduction to likelihood function and why they are important, what does mean to put constraints in the likelihood, how to get likelihood from PyMC3 and what is the correspondent input.
