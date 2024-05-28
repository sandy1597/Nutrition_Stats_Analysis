## Summary
This project simulates a preferential attachment model using R. The goal is to understand the behavior of nodes in a graph where new nodes prefer to attach to existing nodes with higher degrees. The project performs simulations to generate edge distributions and affinity matrices for different numbers of nodes and visualizes the results.

## Simulation Code
The simulation is run for 10,000 iterations with 15 nodes and 1,000 iterations with 100 nodes. The preferential attachment process is implemented, and the resulting edge distributions and affinity matrices are analyzed.

### Questions Answered
1. How do initial nodes influence the probability of connection in a preferential attachment model?
The simulations demonstrate that initial nodes have a higher probability of acquiring connections, which increases their likelihood of receiving even more connections in subsequent iterations.

2. What is the edge distribution of nodes in a preferential attachment model?
The edge distributions for different nodes are plotted, showing how the number of connections varies across simulations. Histograms illustrate the skewness of the distribution, particularly for nodes added later in the process.

4. How can we create and interpret an affinity matrix in this context?
An affinity matrix is created to represent the similarity or closeness of nodes in the graph. The matrix indicates the number of simulations in which pairs of nodes are connected, providing insights into the network's structure.
