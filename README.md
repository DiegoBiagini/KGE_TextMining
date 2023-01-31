# Knowledge Graph Embeddings
Project work for the course Text Mining, DM, BDA.  
A comparison of Knowledge Graph Embedding methods.
# Dataset

We use the triplets Wikidata50k dataset as built in this repository https://github.com/migalkin/StarE.  
The same dataset can be found in PyKeen.  

As for the entity and relation descriptions, they are downloaded from Wikimedia+Wikipedia. 
For posterity they are also found in the `data` folder.  
Before adding them to the notebook folder extract the files `entity_texts.7z` and `entity_to_text.7z`

# Method

We want to assess the performance of classical KGE methods like TransE, DistMult, ConvE as implemented in the PyKeen library when compared with neural methods which also have textual information for the entities(and relations) in the knowledge graph.  
The reference for the latter is: KEPLER: A Unified Model for Knowledge Embedding and Pre-trained Language Representation (https://arxiv.org/pdf/1911.06136.pdf)

In this latter part different transformer models were explored, in particular efficient transformers since we need to embed an entire wikipedia article and that won't usually fit into a BERT context length.

Main libraries used:
- PyKeen
- Pytorch
- transformers
