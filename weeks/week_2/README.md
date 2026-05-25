# Week 2 &mdash; Learning on Graphs

**Focus:** Graph Neural Network basics, adjacency matrices, spectral theory.

## Contents

- [`theory.ipynb`](theory.ipynb) &mdash; mathematical foundations and derivations.
- [`implementation.ipynb`](implementation.ipynb) &mdash; practical Python code, empirical verification, and exercises.

## Topics Covered

1. Graphs and their adjacency, degree, and Laplacian matrices.
2. The graph Laplacian as a discrete Laplace operator; the Dirichlet energy.
3. The graph Fourier transform from the Laplacian eigenbasis.
4. Spectral graph convolution and its computational drawbacks.
5. Polynomial (Chebyshev) filters and the bridge to spatial GNNs.

## Requirements

NumPy, SciPy, NetworkX (no PyTorch Geometric required).

## How to Use

Work through `theory.ipynb` first to build the conceptual and mathematical foundation, then open `implementation.ipynb` to see the ideas realised in code. Each implementation notebook ends with exercises that extend the material.

---

Part of [**Geometric Deep Learning: From Foundations to Applications**](../../README.md) by [@HAYDARKILIC](https://github.com/HAYDARKILIC).
