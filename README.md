# Drug-Target Interaction Prediction: Graph Embeddings

> **MSc Thesis Project** - _George Michoulis_

## 🧬 Project Overview

This research project introduces a novel computational approach for predicting **Drug-Target Interactions (DTI)** using **Graph Neural Networks** and **Graph Embeddings**. By representing drugs and proteins as nodes in a heterogeneous network, the model learns low-dimensional vector representations that capture complex biological relationships, accelerating the process of **In Silico Drug Discovery**.

## 🔑 Key Features

- **Graph Embedding Learning**: Utilizes advanced techniques (e.g., node2vec, GCNs) to encode molecular structures into dense vectors.
- **Heterogeneous Networks**: Models the DTI problem as a link prediction task on a bipartite graph.
- **High-Dimensional Data Processing**: Handles large-scale biological datasets (UniProt, DrugBank).
- **Performance Optimization**: Efficient pickling and data loading strategies for managing GB-sized feature sets.

## 🛠️ Tech Stack & Skills

- **Language**: Python
- **Machine Learning**: PyTorch Geometric / TensorFlow, Scikit-Learn
- **Bioinformatics**: RDKit, Biopython
- **Data Processing**: Pandas, NumPy, Pickle

## 💡 Innovation

Traditional DTI methods rely on hand-crafted features. This "End-to-End Learning" approach automatically discovers latent features from the topological structure of the interaction graph, offering a significant accuracy boost in identifying potential therapeutic candidates for repurposed drugs.

## 📄 Main Entry Point

- `LP-DTI.ipynb`: Link Prediction notebook containing the core experiment loop.
