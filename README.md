### Accompaniment code to my paper "Estimating the Personalised PageRank Matrix". 

## Abstract 

For this project I developed an algorithm that estimates the personalised vectors of a graph, which is a measure of relative importance between pairs of nodes. 
While calculating each individual personalised PageRank vector is computationally expensive, the proposed algorithm estimates all personalised PageRank vectors at the same time in the form of the Personalised PageRank Matrix. 
For the tested graphs, the algorithm was a lot faster than calculating the personalised PageRank vectors while producing similar rankings of relative importance. 
The key to deriving the algorithm is a previously unexplored iterative process where we repeatedly calculate the Personalised PageRank Matrix of a Personalised PageRank Matrix. 
By making an educated guess about the matrix this process is expected to converge to, we can estimate the first iteration, i.e., the Personalised PageRank Matrix of the original graph.
