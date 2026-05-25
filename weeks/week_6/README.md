# Week 6 &mdash; Final Project &mdash; Shape Segmentation on 3D Meshes

**Focus:** Shape segmentation on 3D mesh data using GNNs.

## Contents

- [`theory.ipynb`](theory.ipynb) &mdash; mathematical foundations and derivations.
- [`implementation.ipynb`](implementation.ipynb) &mdash; practical Python code, empirical verification, and exercises.

## Topics Covered

1. Framing mesh segmentation as graph node classification.
2. Engineering isometry-invariant intrinsic features (HKS, eigenfunctions).
3. A permutation-equivariant GNN segmenter (GCN/GAT).
4. Evaluation with per-vertex accuracy and mean IoU.
5. Verifying deformation robustness &mdash; closing the loop on the whole course.

## Requirements

PyTorch + PyTorch Geometric + SciPy (full segmentation pipeline).

## How to Use

Work through `theory.ipynb` first to build the conceptual and mathematical foundation, then open `implementation.ipynb` to see the ideas realised in code. Each implementation notebook ends with exercises that extend the material.

---

Part of [**Geometric Deep Learning: From Foundations to Applications**](../../README.md) by [@HAYDARKILIC](https://github.com/HAYDARKILIC).
