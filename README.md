# GNN study

- 기간: 2022.08.01 ~
- 내용: cs224w 강의

# Road

### Tutorial

- Code
  - [`networkx`](./cs224w_code/CS224W_Colab_0/NetworkX.ipynb)
  - [`torch_geometric`](./cs224w_code/CS224W_Colab_0/PyTorch_Geometric.ipynb)

### Node Embeddings

- Lecture
  - [3.1 - Node Embeddings](https://www.youtube.com/watch?v=rMq21iY61SE&list=PLoROMvodv4rPLKxIpqhjhPgdQy7imNkDn&index=7)
  - [3.2 - Random Walk Approaches for Node Embeddings](https://www.youtube.com/watch?v=Xv0wRy66Big&list=PLoROMvodv4rPLKxIpqhjhPgdQy7imNkDn&index=8&t=1s)
  - [3.3 - Embedding Entire Graphs](https://www.youtube.com/watch?v=eliMLfJeu7A&list=PLoROMvodv4rPLKxIpqhjhPgdQy7imNkDn&index=9&t=970s)
- Code
  - [cs224w HW colab 1](./cs224w_code/CS224W_Colab_1.ipynb)

### PageRank

- Lecture
  - [4.1 - PageRank](https://www.youtube.com/watch?v=TU0ankRcHmo&list=PLoROMvodv4rPLKxIpqhjhPgdQy7imNkDn&index=10)
  - [4.2 - PageRank: How to Solve?](https://www.youtube.com/watch?v=rK2ZBmQHVVs&list=PLoROMvodv4rPLKxIpqhjhPgdQy7imNkDn&index=11)
  - [4.3 - Random Walk with Restarts](https://www.youtube.com/watch?v=HbzQzUaJ_9I&list=PLoROMvodv4rPLKxIpqhjhPgdQy7imNkDn&index=12)
  - [4.4 - Matrix Factorization and Node Embeddings](https://www.youtube.com/watch?v=r12qJZZVtqc&list=PLoROMvodv4rPLKxIpqhjhPgdQy7imNkDn&index=13)

### Node Classificaiton

- Lecture
  - [5.1 - Message passing and Node Classification](https://www.youtube.com/watch?v=6g9vtxUmfwM&list=PLoROMvodv4rPLKxIpqhjhPgdQy7imNkDn&index=14)
  - [5.2 - Relational and Iterative Classification](https://www.youtube.com/watch?v=QUO-HQ44EDc&list=PLoROMvodv4rPLKxIpqhjhPgdQy7imNkDn&index=15)
  - [5.3 - Collective Classification](https://www.youtube.com/watch?v=kh3I_UTtUOo&list=PLoROMvodv4rPLKxIpqhjhPgdQy7imNkDn&index=16)

### GNN

- Lecture
  - [6.1 - Introduction to Graph Neural Networks](https://www.youtube.com/watch?v=F3PgltDzllc&list=PLoROMvodv4rPLKxIpqhjhPgdQy7imNkDn&index=17)
  - [6.2 - Basics of Deep Learning](https://www.youtube.com/watch?v=tutlI9YzJ2g&list=PLoROMvodv4rPLKxIpqhjhPgdQy7imNkDn&index=18)
  - [6.3 - Deep Learning for Graphs](https://www.youtube.com/watch?v=MH4yvtgAR-4&list=PLoROMvodv4rPLKxIpqhjhPgdQy7imNkDn&index=19)
  - [7.1 - A general Perspective on GNNs](https://www.youtube.com/watch?v=RU9uTa_-ZOw&list=PLoROMvodv4rPLKxIpqhjhPgdQy7imNkDn&index=20)
  - [7.2 - A Single Layer of a GNN](https://www.youtube.com/watch?v=247Mkqj_wRM&list=PLoROMvodv4rPLKxIpqhjhPgdQy7imNkDn&index=21)
  - [7.3 - Stacking layers of a GNN](https://www.youtube.com/watch?v=ew1cnUjRgl4&list=PLoROMvodv4rPLKxIpqhjhPgdQy7imNkDn&index=22)
  - [8.1 - Graph Augmentation for GNNs](https://www.youtube.com/watch?v=1A6VoEkQnhQ&list=PLoROMvodv4rPLKxIpqhjhPgdQy7imNkDn&index=23)
  - [8.2 - Training Graph Neural Networks](https://www.youtube.com/watch?v=eXIIH8YVxKI&list=PLoROMvodv4rPLKxIpqhjhPgdQy7imNkDn&index=24)
  - [8.3 - Setting up GNN Prediction Tasks](https://www.youtube.com/watch?v=ewEW_EMzRuo&list=PLoROMvodv4rPLKxIpqhjhPgdQy7imNkDn&index=25)
  - [9.1 - How Expressive are Graph Neural Networks](https://www.youtube.com/watch?v=5vMEgYbka0A&list=PLoROMvodv4rPLKxIpqhjhPgdQy7imNkDn&index=26)
  - [9.2 - Designing the Most Powerful GNNs](https://www.youtube.com/watch?v=B5y47gWt3co&list=PLoROMvodv4rPLKxIpqhjhPgdQy7imNkDn&index=27)
- Code
  - [cs224w HW colab 2](./cs224w_code/CS224W_Colab_2.ipynb)
    - GCN
  - [cs224w HW colab 3](./cs224w_code/CS224W_Colab_3.ipynb)
    - GraphSAGE
    - GAT
- Summary
  - [GCN](https://minsoo9506.github.io/01_gnn/)
  - [GraphSAGE](https://minsoo9506.github.io/02_graphsage/)
  - [GAT](https://minsoo9506.github.io/03_gat/)
- Paper
  - [Design Space of Graph Neural Networks, NIPS 2020](https://proceedings.neurips.cc/paper/2020/file/c5c3d4fe6b2cc463c7d7ecba17cc9de7-Paper.pdf)
  - `GCN`: [Semi-Supervised Classification with Graph Convolutional Networks, ICLR 2017](https://arxiv.org/abs/1609.02907)
  - `GraphSAGE`: [Inductive Representation Learning on Large Graphs, NIPS 2017](https://proceedings.neurips.cc/paper/2017/file/5dd9db5e033da9c6fb5ba83c7a7ebea9-Paper.pdf)
  - `GAT`: [Graph Attention Networks, ICLR 2018](https://arxiv.org/abs/1710.10903)
  - `Batch Normalization`: [Batch Normalization: Accelerating Deep Network Training by Reducing Internal Covariate Shift, ICML 2015](https://arxiv.org/abs/1502.03167)
  - `Dropout`: [Dropout: A Simple Way to Prevent Neural Networks from Overfitting, JMLR 2014](https://jmlr.org/papers/v15/srivastava14a.html)
  - `Skip connection`: [Deep Residual Learning for Image Recognition](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)
  - `Skip connection in Graph`: [Representation Learning on Graphs with Jumping Knowledge Networks, ICML 2018](https://proceedings.mlr.press/v80/xu18c/xu18c.pdf)
  - `GIN`: [HOW POWERFUL ARE GRAPH NEURAL NETWORKS?, ICLR 2019](https://arxiv.org/pdf/1810.00826.pdf)

### Heterogeneous Graphs, Knowledge Graph Embeddings

- Lecture
  - [10.1-Heterogeneous & Knowledge Graph Embedding](https://www.youtube.com/watch?v=Rfkntma6ZUI&list=PLoROMvodv4rPLKxIpqhjhPgdQy7imNkDn&index=28)
  - [10.2 - Knowledge Graph Completion](https://www.youtube.com/watch?v=xop5tC9T5xM&list=PLoROMvodv4rPLKxIpqhjhPgdQy7imNkDn&index=29)
  - [10.3 - Knowledge Graph Completion Algorithms](https://www.youtube.com/watch?v=Xm5VrxZYhu4&list=PLoROMvodv4rPLKxIpqhjhPgdQy7imNkDn&index=30)
  - [11.1 - Reasoning in Knowledge Graphs](https://www.youtube.com/watch?v=X9yl0pTP9fY&list=PLoROMvodv4rPLKxIpqhjhPgdQy7imNkDn&index=31)
  - [11.2 - Answering Predictive Queries](https://www.youtube.com/watch?v=qaRIBNE-4Ho&list=PLoROMvodv4rPLKxIpqhjhPgdQy7imNkDn&index=32)
  - [11.3 - Query2box: Reasoning over KGs](https://www.youtube.com/watch?v=Nt66M2OsbCw&list=PLoROMvodv4rPLKxIpqhjhPgdQy7imNkDn&index=33)
- Paper
  - `TranE`: [Translating Embeddings for Modeling Multi-relational Data](https://proceedings.neurips.cc/paper/2013/file/1cecc7a77928ca8133fa24680a88d2f9-Paper.pdf)
  - `TranR`: [Learning Entity and Relation Embeddings for Knowledge Graph Completion](https://linyankai.github.io/publications/aaai2015_transr.pdf)
  - `DistMult`: [Embedding Entities and Relations for Learning and Inference in Knowledge Bases](https://arxiv.org/abs/1412.6575)
  - `ComplEx`: [Complex Embeddings for Simple Link Prediction](https://arxiv.org/abs/1606.06357)
  - [Traversing Knowledge Graphs in Vector Space](https://arxiv.org/abs/1506.01094)
  - [Embedding Logical Queries on Knowledge Graphs](https://arxiv.org/abs/1806.01445)
  - [Query2box: Reasoning over Knowledge Graphs in Vector Space using Box Embeddings](https://arxiv.org/abs/2002.05969)

# Reference

- [cs224w 강의](https://www.youtube.com/playlist?list=PLoROMvodv4rPLKxIpqhjhPgdQy7imNkDn)
- [Graph Representation Learning Book](https://www.cs.mcgill.ca/~wlh/grl_book/)
