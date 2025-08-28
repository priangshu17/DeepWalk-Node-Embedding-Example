# DeepWalk-Node-Embedding-Example

This repository contains a Jupyter Notebook that implements the **DeepWalk** algorithm from its core components. The project serves as an educational guide to learning latent representations (embeddings) for nodes in a graph, which can then be used as features in downstream machine learning tasks.

## 📝 Overview

DeepWalk is a foundational algorithm for learning continuous vector representations for nodes in a network. The core idea is to generate sequences of nodes using random walks and then apply language modeling techniques (like Skip-Gram) to these sequences to learn an embedding for each node.

This notebook walks through the entire pipeline:
1.  **Graph Creation**: Building a graph structure.
2.  **Random Walk Generation**: Creating a corpus of node sequences.
3.  **Embedding Learning**: Training a model on the walks to generate node vectors.
4.  **Evaluation**: Using the learned embeddings as features for a downstream node classification task.
5.  **Visualization**: Using PCA to project the high-dimensional embeddings into 2D for visualization.
