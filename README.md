# Entity Summarization

## Extractive Entity Summarization
### Shortly brief of entity summarization

Based on the distributed RDF dataset statistics, more than 10.000 datasets are following Semantic Web standards. 
It provides a billion triples (RDF data) that are used by many applications to provide information to the human. 
Avoiding information overload on the data consumers [[1]](#1) and making it more concise and recapitulative [[2]](#2) are some reasons used by researchers to conduct research on Entity Summarization. 
Entity summarization is a technique to establish short summary (of) RDF data [[2]](#2)[[3]](#3) so that users are able to identify the underlying identity quickly [[3]](#3). 
Comparing to document summarization where the data is unstructured and there are many frequent words, entity summarization works on RDF that is structured and without frequent terms. 
Many researchers have been conducted researches on individual entity to produce entity summaries. Generally, there are two categories of entity summarization methods, namely, supervised learning and unsupervised learning. 

### Survey
**2021**

Entity Summarization: State of the Art and Future Challenges \
Paper: https://www.sciencedirect.com/science/article/abs/pii/S1570826821000226

### Unsupervised learning

**2010**

DIVERSUM: Towards diversified summarisation of entities in knowledge graphs \
Paper: https://sci-hub.tw/10.1109/ICDEW.2010.5452707

**2011**

RELIN: RELatedness and Informativeness-based centrality for entity summarizatioN [[3]](#3) \
Paper: http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.352.7610&rep=rep1&type=pdf

**2015**

FACES: diversity-aware entity summarization using incremental hierarchical conceptual clustering \
Paper: https://www.aaai.org/ocs/index.php/AAAI/AAAI15/paper/view/9562/9233

**2016**

Linksum: Using link analysis to summarize entity data [[6]](#6) \
Paper: https://www.aifb.kit.edu/images/4/43/LinkSUM.pdf

**2017**

Dynamic Factual Summaries for Entity Cards \
Code: https://github.com/iai-group/DynamicEntitySummarization-DynES \
Paper: https://dl.acm.org/doi/10.1145/3077136.3080810

ESLDA: entity summarization using knowledge-based topic modeling \
Paper: https://www.aclweb.org/anthology/I17-1032.pdf


Semantics-based Entity Summarization \
Paper: https://kalpagunaratna.github.io/swsa_files/swsa_short_paper-Kalpa.pdf

**2018**

Entity Summarization Based on Formal Concept Analysis \
Code: https://github.com/kekeeo/KAFCA \
Paper: http://semanticweb.kaist.ac.kr/home/images/c/cb/Entity_Summarization_Based_on_Formal_Concept_Analysis.pdf

BAFREC: Balancing Frequency and Rarity for Entity Characterization in Open Linked Data \
Paper: http://www.ifis.cs.tu-bs.de/sites/default/files/eyre2018-kroll-BAFREC-camera-ready.pdf

Combining Word Embedding and Knowledge-Based Topic Modeling for Entity Summarization \
Paper: https://ieeexplore.ieee.org/document/8334467

MPSUM: Entity Summarization with Predicate-based Matching \
Code: https://github.com/WeiDongjunGabriel/MPSUM.git \
Paper: https://arxiv.org/abs/2005.11992

PageRank and Generic EntitySummarization for RDF Knowledge Bases \
Paper: https://link.springer.com/chapter/10.1007/978-3-319-93417-4_10

**2020**

Entity Summarization in Fuzzy Knowledge Graph Based on Fuzzy Concept Analysis \
Paper: https://link.springer.com/chapter/10.1007/978-981-15-9309-3_3

**2021**

Incremental Entity Summarization with Formal Concept Analysis \
Paper: https://ieeexplore.ieee.org/document/9459533

Entity Summarization in Fuzzy Knowledge Graph Based on Fuzzy Concept Analysis\
Paper: https://link.springer.com/chapter/10.1007%2F978-981-15-9309-3_3

### Supervised Learning
**2019**

ESA:Entity Summarization Attention [[2]](#2) \
Code: https://github.com/WeiDongjunGabriel/ESA \
Paper: https://arxiv.org/abs/1905.10625 

**2020**

DeepLENS: Deep Learning for Entity Summarization \
Code: https://github.com/nju-websoft/DeepLENS \
Paper: https://arxiv.org/abs/2003.03736

Entity Summarization with User Feedback \
Code: https://github.com/nju-websoft/DRESSED \
Paper: https://link.springer.com/content/pdf/10.1007%2F978-3-030-49461-2.pdf

Neural Entity Summarization with Joint Encoding and Weak Supervision \
Code: https://github.com/lijunyou/IJCAI2020 \
Paper: https://www.ijcai.org/Proceedings/2020/0228.pdf

AutoSUM: Automating Feature Extraction and Multi-user Preference for Entity Summarization \
Code: https://github.com/WeiDongjunGabriel/AutoSUM \
Paper: https://link.springer.com/chapter/10.1007%2F978-3-030-47436-2_44

**2021**

GATES: Graph Attention Networks for Entity Summarization \
Code: https://github.com/dice-group/GATES \
Paper: https://dl.acm.org/doi/10.1145/3460210.3493574

**2023**

ESCS: Entity Summarization via Exploiting Description Complementary and Salience \
Paper: https://ieeexplore.ieee.org/document/9718581

**2024**

ESLM: Improving Entity Summarization by Leveraging Language Models \
Code: https://github.com/dice-group/ESLM \
Paper: https://papers.dice-research.org/2024/ESWC_ESLM/public.pdf


### Benchmark Datasets

### ESBM Benchmark 
2020
Paper: https://link.springer.com/chapter/10.1007/978-3-030-49461-2_32

#### ESBM Benchmark v.1.1
Code: https://github.com/nju-websoft/ESBM/tree/master/v1.1

#### ESBM Benchmark V.1.2
Code: https://github.com/nju-websoft/ESBM/tree/master/v1.2

### FACES Dataset
Original source: http://wiki.knoesis.org/index.php/FACES \
Backup of original source: https://files.dice-research.org/users/asep/datasets/entity-summarization/original_faces_dataset.zip \
Source: https://github.com/dice-group/GATES/tree/main/data/FACES

### Wiki Entity Summarization Benchmark
2024 \
Paper: https://arxiv.org/abs/2406.08435 \
Code: https://github.com/msorkhpar/wiki-entity-summarization \
Toolkit: https://github.com/msorkhpar/wiki-entity-summarization-toolkit 

## Multi-Entity Summarization

### Extractive Multi Entity Summarization

**2017**

REMES: Relatedness-based multi entity summarization \
Paper: https://www.ijcai.org/Proceedings/2017/147

Micro-review synthesis for multi-entity summarization \
Paper: https://link.springer.com/article/10.1007/s10618-017-0491-4 

## Abstractive Entity Summarization

### Datasets
Using Pre-trained Language Models for Abstractive DBPEDIA Summarization: A Comparative Study \
Paper: https://papers.dice-research.org/2023/SEMANTICS_LLM_DBpedia/main_public.pdf \
Resources: https://zenodo.org/records/7441120

# Knowledge Graph Summarization

**2020**

VISION-KG: Topic-centric Visualization System for Summarizing Knowledge Graph \
Paper: https://dl.acm.org/doi/pdf/10.1145/3336191.3371863

**2024** 

A Survey on Extractive Knowledge Graph Summarization: Applications, Approaches, Evaluation, and Future Directions \
Paper:https://arxiv.org/abs/2402.12001

## References

<a id="1">[1]</a> 
Gunaratna, K., Yazdavar, A. H., Thirunarayan, K., Sheth, A., & Cheng, G. (2017, August). 
Relatedness-based multi-entity summarization. 
In IJCAI: proceedings of the conference (Vol. 2017, p. 1060). NIH Public Access.

<a id="2">[2]</a> 
Wei, D., & Liu, Y. (2019).
ESA: Entity Summarization with Attention.
arXiv preprint arXiv:1905.10625.

<a id="3">[3]</a> 
Cheng, G., Tran, T., & Qu, Y. (2011, October).
Relin: relatedness and informativeness-based centrality for entity summarization.
In International Semantic Web Conference (pp. 114-129). Springer, Berlin, Heidelberg.

<a id="4">[4]</a> 
Liu, Q., Cheng, G., Gunaratna, K., & Qu, Y. (2019).
Entity Summarization: State of the Art and Future Challenges.
arXiv preprint arXiv:1910.08252.

<a id="5">[5]</a> 
Gunaratna, K., Thirunarayan, K., & Sheth, A. (2015, February).
FACES: diversity-aware entity summarization using incremental hierarchical conceptual clustering.
In Twenty-Ninth AAAI Conference on Artificial Intelligence.

<a id="6">[6]</a> 
Thalhammer, A., Lasierra, N., & Rettinger, A. (2016, June).
Linksum: using link analysis to summarize entity data.
In International Conference on Web Engineering (pp. 244-261). Springer, Cham.

