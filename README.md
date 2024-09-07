# Monte-Carlo-Markov-Chain-Implementation

With the countless breakthroughs and increased interest in machine learning and artificial intelligence applications across the world, statistics and probability has become a focus as that is the engine that runs the algorithms that let us do novel analysis on old problems to obtain new findings. But as a result, many of these problems in probability are very messy or unsolvable. Most notably, the high dimensional probability distributions that are fueled by the huge datasets we have, have non elementary and unsolvable integrals, or integrals so computationally expensive that they are not worth computing. Monte Carlo Markov Chain methods combat this issue, using sophisticated monte carlo techniques to construct approximates of complicated probability distributions, close enough for applicable use. Here I demonstrate one of these methods, the Metropolis-Hastings algorithm, on a simple well defined distribution.

## Metropolis-Hastings Algorithm

The Metropolis-Hastings Algorithm is arguably one of the most popular MCMC algorithms due to its simplicity, uniqueness, and effectiveness. It involves constructing a markov chain, using a function that is proportional to the target distribution to determine 
