# Geometric Deep Learning: From Foundations to Applications

This repository contains a comprehensive **6-week course on Geometric Deep Learning (GDL)**, designed to bridge the gap between theoretical manifold learning and modern deep learning architectures.

---

## Course Overview

Geometric Deep Learning aims to generalize deep learning techniques to non-Euclidean data structures&mdash;such as graphs and manifolds&mdash;by leveraging the symmetry properties of the underlying space. This course provides a solid mathematical foundation followed by hands-on implementations using **PyTorch Geometric**.

The unifying theme is the **GDL blueprint** of Bronstein et al.: *identify the data domain and its symmetry group, then design layers that are equivariant to that group.* Each week instantiates this blueprint on a new domain&mdash;grids, graphs, point clouds, and manifolds.

## 6-Week Syllabus

| Week | Topic | Focus |
|------|-------|-------|
| **1** | [Geometric Priors and Symmetry](weeks/week_1) | Manifolds, equivariance, and symmetry groups (`SO(3)`, `SE(3)`). |
| **2** | [Learning on Graphs](weeks/week_2) | Graph Neural Network (GNN) basics, adjacency matrices, spectral theory. |
| **3** | [Message Passing and Spatial GNNs](weeks/week_3) | MPNN framework, permutation invariance, GCN, and GAT. |
| **4** | [3D Data and Point Clouds](weeks/week_4) | Deep learning on 3D objects, rotation equivariance, PointNet. |
| **5** | [Manifolds and Riemannian Geometry](weeks/week_5) | Tangent spaces, Laplace&ndash;Beltrami operator, and gradient flow. |
| **6** | [Final Project](weeks/week_6) | Shape segmentation on 3D mesh data using GNNs. |

## Repository Structure

Each week lives in its own folder under `weeks/`, containing two notebooks:

```
geometric-deep-learning/
├── weeks/
│   ├── week_1/
│   │   ├── theory.ipynb           # Mathematical foundations and derivations
│   │   ├── implementation.ipynb   # Practical Python code and exercises
│   │   └── README.md
│   ├── week_2/ ...
│   └── week_6/
├── requirements.txt
├── environment.yml
├── LICENSE
├── CONTRIBUTING.md
└── .github/workflows/notebooks.yml
```

- **`theory.ipynb`** &mdash; mathematical foundations and derivations (LaTeX throughout).
- **`implementation.ipynb`** &mdash; practical Python code, empirical verification, and exercises.

## Technical Stack

- **Framework:** PyTorch &amp; PyTorch Geometric (PyG)
- **Tools:** NetworkX, NumPy, SciPy, Matplotlib
- **Documentation:** Jupyter Notebooks (LaTeX included for mathematical derivations)

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/HAYDARKILIC/geometric_deep_learning.git
cd geometric_deep_learning
```

### 2. Install dependencies

Using `pip`:

```bash
pip install -r requirements.txt
```

> **Note on PyTorch Geometric.** PyG ships platform/CUDA-specific wheels. If `pip install torch_geometric` does not resolve all extensions on your system, follow the [official installation guide](https://pytorch-geometric.readthedocs.io/en/latest/install/installation.html). The Week 1, 2, and 5 notebooks run without PyG (NumPy/SciPy only); PyG is required from Week 3 onward.

### 3. Launch Jupyter

```bash
jupyter lab          # or: jupyter notebook
```

Open any week's `theory.ipynb` first, then work through `implementation.ipynb`.

## Academic References

- Bronstein, M. M., Bruna, J., Cohen, T., &amp; Veli&#269;kovi&#263;, P. (2021). *Geometric Deep Learning: Grids, Groups, Graphs, Geodesics, and Gauges.* arXiv:2104.13478.
- Hamilton, W. L. (2020). *Graph Representation Learning.* Morgan &amp; Claypool.
- Kipf, T. N., &amp; Welling, M. (2017). *Semi-Supervised Classification with Graph Convolutional Networks.* ICLR.
- Veli&#269;kovi&#263;, P., et al. (2018). *Graph Attention Networks.* ICLR.
- Qi, C. R., et al. (2017). *PointNet: Deep Learning on Point Sets for 3D Classification and Segmentation.* CVPR.

A complete, per-topic reference list is included at the end of each `theory.ipynb`.

## License

This project is licensed under the MIT License &mdash; see the [LICENSE](LICENSE) file for details.
