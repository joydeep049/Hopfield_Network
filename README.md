## Recalling Patterns Using Associative Memory

This project aims to develop an efficient Hopfield Networks, which was pretty neat work. 
Although it doesn't actually understand the underlying Distribution, the concept of memory in a Non-Probablilistic 
setting using Non-Probabilistic dimensional strectch to learn and converge patterns.

Hopfield Networks were developed by John Hopfield in 1982. They we meant to model our brain in terms of how reaches an associated memory starting from small and noisy fragments. 

They are Artificial Recurrent Neural Networks which trained by the Hebbian Principle. 

There are mainly two phases when it comes to associative memory.

1. Training
   The Weight matrix is updated based on the patterns we want to store. It changes its value corressponding to every pattern we want to store.

   (Detailed Explanation coming soon)

2. Inference
   This checks the ability of the Hopfield Network to collapse to the nearest associated memory.


#### Memory Limit
    For a network with `N` nodes, the memory limit is `0.15N`

#### Disadvantages
1. They do not take into account the stochastic nature of the human neural network. The actual brain has stochastic neurons, which means it can randomly send a signal or remain dormant. This fact points towards probabilistic models to imitate the human brain. Further words, like Restricted Boltzmann Machines take into account the random nature of neurons. 

2. It is computationally expensive to train a Hopfield Network to memorize even a simple natural pattern.


#### Whats the future
I am going to continue adding more and more usecases of how the hopfield network can model complex patterns. Stay Tuned!


