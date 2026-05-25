# Week 3 &mdash; Message Passing and Spatial GNNs

**Focus:** The MPNN framework, permutation invariance, GCN, and GAT.

## Contents

- [`theory.ipynb`](theory.ipynb) &mdash; mathematical foundations and derivations.
- [`implementation.ipynb`](implementation.ipynb) &mdash; practical Python code, empirical verification, and exercises.

## Topics Covered

1. The Message Passing Neural Network framework: message, aggregate, update.
2. Permutation equivariance as the defining symmetry of graphs.
3. The Graph Convolutional Network (GCN) and its renormalisation.
4. The Graph Attention Network (GAT) and learned aggregation.
5. Expressive power and the Weisfeiler&ndash;Lehman bound (GIN).

## Requirements

PyTorch + PyTorch Geometric (trains GCN and GAT on Cora).

## How to Use

Work through `theory.ipynb` first to build the conceptual and mathematical foundation, then open `implementation.ipynb` to see the ideas realised in code. Each implementation notebook ends with exercises that extend the material.

---

Part of [**Geometric Deep Learning: From Foundations to Applications**](../../README.md) by [@HAYDARKILIC](https://github.com/HAYDARKILIC).
