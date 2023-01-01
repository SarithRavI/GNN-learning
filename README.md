# GNN Learning
## _Repository containing custom implementations of Graph Neural Networks._


In this repository I include custom implementations of Graph Neural Networks, with either Tensorflow/ Spektral or Pytorch/ PyG.

```bash
root
│   README.md
│
├───images
└───notebooks
        GCN.ipynb
        GCN_with_lambda.ipynb

```
Interactive Jupyter notebooks of implementations are contained in the 'notebooks' subdirectory.

## Implementations

| File name | Description | Paper | Status |
| ------ | ------ |------|------|
| GCN | Usual layerwise propagation rule wich can be motivated via a first-order approximation of localized spectral filters on graphs.(see Section 2) | Semi-Supervised Classification with Graph Convolutional Networks [https://arxiv.org/pdf/1609.02907.pdf][PlGh]| Complete |
| GCN_with_lambda | Propagation rule with trade-off constant λ, which gives different weights to self loop connection and neighbor connections. (See Section 7.2 end)  | Semi-Supervised Classification with Graph Convolutional Networks [https://arxiv.org/pdf/1609.02907.pdf][PlGh] | Complete |
