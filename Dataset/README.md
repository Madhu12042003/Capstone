## PICKLE
<p align="center">
<img align="center" width="392" alt="image" src="https://github.com/user-attachments/assets/a7603098-84b5-4279-8cc8-e2b52df3b18e">
<br>
<br>
</p>


The PICKLE dataset (Plant-science Information Corpus with Knowledge graph and Linked data Enrichment) is a comprehensive, 
open-source corpus created to advance natural language processing (NLP) in the plant sciences. It comprises **250 research 
abstracts** annotated with **6,245 entities** and **2,149 relationships**, all manually labeled by domain experts to ensure 
high accuracy and relevance. This dataset is particularly suitable for knowledge graph completion tasks because its 
**gold-standard annotations** provide reliable data for training models to predict missing links between entities. PICKLE's diverse and rich coverage of entities, such as plant species, traits, and experimental conditions, along with a 
variety of relations, enables models to capture the complexities of plant science data. The domain-specific focus of the 
dataset allows for precise modeling of the unique terminology and relationships inherent in plant science. 

Furthermore, PICKLE supports relation extraction (RE) and named entity recognition (NER) tasks, enabling models to extract 
structured knowledge from unstructured text, which is essential for populating and updating knowledge graphs. By offering a 
detailed mapping of plant science entities and relationships, PICKLE aids in augmenting incomplete knowledge graphs, filling
in missing entities or relations, and contributing to more comprehensive and accurate plant science knowledge representations. 
Its combination of high-quality annotations, domain relevance, and applicability to both entity and relation extraction makes 
PICKLE an invaluable resource for knowledge graph completion in the plant science.

## Fb15k-237
<p align="center">
<img align="center" width="492" alt="image" src="https://github.com/user-attachments/assets/e238572d-ced8-4bee-a0c0-b4a9e6a89939">
<br><br>
</p>

The FB15k-237 dataset, created by Kristina et al., is a refined version of the original FB15k dataset, designed to improve
knowledge graph completion tasks by addressing the issue of test set leakage, which was present in the original dataset
due to the inclusion of inverse/duplicate relations.  The dataset consists of **310,079 triples** with **14,505 entities** and **237
relation types**, offering a diverse and rich structure for evaluating models' abilities to handle a variety of entity and 
relation interactions. The inclusion of textual mentions derived from 200 million sentences from the **ClueWeb12 corpus**, coupled 
with **Freebase entity mention annotations**, enhances the dataset's utility for models that leverage unstructured text alongside 
structured triples, promoting the development of models that better understand the semantic context of relationships. 


This combination of structured data with real-world textual context makes FB15k-237 particularly suitable for
tasks such as link prediction, where models must infer missing entities or relations. Its complexity ensures that models need
to capture deeper semantic patterns, making it a valuable resource for cutting-edge KGC techniques like embedding-based models,
graph neural networks, and neural-symbolic approaches. By eliminating redundancy and forcing more generalizable learning, 
FB15k-237 supports the development of models capable of handling realistic knowledge graph completion tasks, making it a widely
adopted and standard benchmark in the research community, driving innovation and comparisons across various KGC methods.
