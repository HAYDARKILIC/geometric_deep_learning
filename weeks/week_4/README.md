# Week 4 &mdash; 3D Data and Point Clouds

**Focus:** Deep learning on 3D objects, rotation equivariance, PointNet.

## Contents

- [`theory.ipynb`](theory.ipynb) &mdash; mathematical foundations and derivations.
- [`implementation.ipynb`](implementation.ipynb) &mdash; practical Python code, empirical verification, and exercises.

## Topics Covered

1. Representations of 3D data: voxels, multi-view, meshes, point clouds.
2. The two symmetries of a point cloud: permutation and rigid motion (SE(3)).
3. PointNet: shared MLP + symmetric pooling, and its permutation invariance.
4. Handling rotation: augmentation, T-Net, invariant features.
5. Toward exact SO(3)-equivariance (Tensor Field Networks).

## Requirements

PyTorch (PointNet from scratch; e3nn optional for extensions).

## How to Use

Work through `theory.ipynb` first to build the conceptual and mathematical foundation, then open `implementation.ipynb` to see the ideas realised in code. Each implementation notebook ends with exercises that extend the material.

---

Part of [**Geometric Deep Learning: From Foundations to Applications**](../../README.md) by [@HAYDARKILIC](https://github.com/HAYDARKILIC).
