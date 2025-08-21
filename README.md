[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DennisWayo/Q-DFTNet/blob/main/q_dftnet.py)
![Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![JCC](https://img.shields.io/badge/Journal%20of%20Computational%20Chemistry-2025-blue)

### Q-DFTNet: Chemistry-Informed Neural Network for Molecular Dipole Prediction

Q-DFTNet is a lightweight, chemistry-informed graph neural network (GNN) framework for predicting molecular dipole moments based on DFT-driven QM9 data. This repository contains implementations of 7 GNN models benchmarked on performance, complexity, and latent space alignment. 

This repository contains a **single, self-contained Python script** that reproduces all key visualizations (performance plots, latent space t-SNE, model complexity vs. accuracy) as presented in the paper.


**This repository supports the article**:  
“Q-DFTNet: A Chemistry-Informed Neural Network Framework for Predicting Molecular Dipole Moments via DFT-Driven QM9 Data”  
Published in *Journal of Computational Chemistry* (Wiley, 2025)

📘 **Read the paper**:  
[https://doi.org/10.1002/jcc.70206](https://doi.org/10.1002/jcc.70206)



**How to Use**:
- Clone or download this repository.
- Run the provided `q_dftnet.py` script in a Python environment (e.g., Google Colab or Jupyter Notebook).
- All plots and metrics will be automatically generated.

> ⚠️ **Note**: Due to differences in Python library versions (e.g., PyTorch Geometric, Matplotlib), **minor variations in plots or metrics may occur**. These differences are expected and do not affect the overall conclusions of the paper.


**Cite this work**:
```bibtex
@article{wayo2025q_dftnet,
  title={Q-DFTNet: A Chemistry-Informed Neural Network Framework for Predicting Molecular Dipole Moments via DFT-Driven QM9 Data},
  author = {Wayo, Dennis D. K. and Mohd Zulkifli Bin M. Noor and Masoud Darvish Ganj and Camila Martins Saporetti and Leonardo Goliatt},
  journal = {Journal of Computational Chemistry},
  year={2025},
  doi={https://doi.org/10.1002/jcc.70206}
}
```

🔒 **Copyright Notice**:

© 2025 Wiley. This repository contains only original code and independently generated visualizations for reproducibility.
No copyrighted figures, tables, or text from the published article are included.
