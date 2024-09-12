## Vector Embedding Generation

Vector embeddings offer a powerful and compact method for representing entities and relationships within a knowledge graph by mapping them into a lower-dimensional continuous space. This technique leverages patterns learned during training to effectively predict missing links and uncover hidden relationships. Each entity and relation is transformed into a vector, allowing mathematical operations—such as addition, subtraction, and dot products—to reveal connections and interactions that were not explicitly present in the original graph data. By applying vector embeddings, machine learning techniques such as clustering, classification, and similarity measurement can be directly employed on knowledge graphs, facilitating advanced analysis and insights. They also help manage high-dimensional data more efficiently, reducing the computational burden associated with large-scale knowledge graphs. This efficiency is crucial for handling extensive datasets, as it mitigates the challenges of high-dimensionality and accelerates the learning process. In our study, we leverage six different embedding types to determine which one performs best with our datasets, evaluating their effectiveness in capturing and representing the complex relationships inherent in the data. 

## Vector Embedding Models 

* **RESCAL (RElational SCALing)** models each entity and relation as tensors, with relations represented by matrices to represent complex interactions, but can be computationally intensive and requires higher number of parameters.
  
* **TransE (TRANSlation-based Embeddings)** models relations as translations in the embedding space, where the head entity plus the relation vector should approximate the tail entity vector, but struggles to represent complex interactions.
  
* **DistMult (DISTant MULTiplcation)** is the bilinear product, modeling relationship between two entities by taking the element-wise product of the entity vectors and a diagonal matrix representing the relation, but struggles with asymmetric relations.
  
* **RotatE (ROTATion-based Embeddings)** uses rotations in the complex plane to model relationships as unitary transformations, allowing for representation of both symmetric and asymmetric relations.
  
* **ComplEx (COMPLex Embeddings)** extends the DistMult model by using complex-valued embeddings instead of real-valued ones, which allows it to model both symmetric as well as asymmetric relations and capture more nuanced patterns in knowledge graphs.
  
* **HolE (HOLographic Embeddings)** uses circular correlation between entity embeddings to capture interactions between them, allowing it to model both symmetric and asymmetric relations, thus striking a balance between parameter efficiency and the ability to model complex interactions.

