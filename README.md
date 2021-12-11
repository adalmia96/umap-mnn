Clustering with UMAP: Why and How Connectivity Matters
==============================

The repo contains the source code needed to reproduce the results in [Clustering with UMAP: Why and How Connectivity Matters](https://arxiv.org/abs/2108.05525) by Dalmia and Sia

## How to use the code
The code for this paper is all implemented in Colab/jupyter notebooks for ease of reading and understanding. All the required modules are included in the firsat section of the notebook

In the colab notebook, we walk you through our modification to the orginial UMAP algorithm (for more specifics on how the UMAP algorithm works and implemented, please refer to the orginial [UMAP repository](https://github.com/lmcinnes/umap) (v0.5+)

There are two different colab notebooks provided in the repository:
1. [Adjacent Neighbors Implementation](https://github.com/adalmia96/umap-mnn/blob/main/code/UMAP_MNN_Adjacent_Neighbors.ipynb)
2. [Path Neighbors Implementation](https://github.com/adalmia96/umap-mnn/blob/main/code/UMAP_MNN_Path_Neighbors.ipynb)

Both implementations contain all the connectivity method (NN<MST-min<MST-all) and can e easily modified to include others 



