# KGE_TextMining
Project work for the course Text Mining, DM, BDA. A comparison of Knowledge Graph Embedding methods.
# Dataset

We use the triplets Wikidata50k dataset as built in this repository https://github.com/migalkin/StarE for computational purposes

# Method

We want to assess the performance of classical KGE methods like TransE etc as implemented in the PyKeen library when compared with neural methods which also have textual information for the entities(and relations) in the knowledge graph.  
The reference for the latter is: KEPLER: A Unified Model for Knowledge Embedding and Pre-trained Language Representation (https://arxiv.org/pdf/1911.06136.pdf)

Furthermore I would like to explore different transformer models on this last approach, in particular efficient transformers since we need to embed an entire wikipedia article and that won't usually fit into a BERT context length.
