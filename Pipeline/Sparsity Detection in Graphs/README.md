## Sparsity Detection in Knowledge Graphs

Sparsity pertains to the imbalance in the distribution of connections among nodes, where certain entities have many relationships while others have few. This imbalance can
indicate incomplete or insufficiently detailed parts of the graph, impacting the effectiveness of the graph for tasks such as inference, recommendation, or semantic search.
Detecting sparsity is crucial for knowledge graph completion because it identifies these gaps, allowing for targeted enrichment strategies to add missing links or enhance
existing connections. Addressing sparsity ensures a more comprehensive and accurate representation of the domain, improving the graph's utility and performance in downstream
applications.

## Gini Index

The Gini Index is a valuable tool for analyzing the distribution of node degrees in knowledge graphs. It quantifies the disparity in the number of connections (edges) each node
(entity) has. This helps in identifying nodes with disproportionately high or low connectivity, which can indicate structural imbalances within the graph. A high Gini index 
indicates a few nodes with a very high number of connections, which could suggest a few dominant entities or hubs in the graph. This can be useful for understanding key players
or influential entities in a network. Conversely, a low Gini index indicates a more even distribution of connections, suggesting a balanced or homogeneous structure. 

The Gini index for node degrees in a knowledge graph is calculated as follows:

* Collect Node Degrees and Sort
* Calculate Cumulative Sums and Normalize
* Determine the Lorenz Curve (Cumulative proportion of Nodes vs. Edges)
* Compute the Gini Index:
  
  <img width="264" alt="image" src="https://github.com/user-attachments/assets/93116487-9e65-4a82-970b-efa009589f5a">


  
