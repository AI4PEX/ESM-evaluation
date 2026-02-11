
# ESM Evaluation Diagnostics

This repository provides machine learning-based evaluation tools for Earth System Models (ESMs), developed under WP4 of the AI4PEX project.

The codebase implements state-of-the-art explainable AI (XAI), causal discovery, and data-driven interpretable analysis methods for evaluating ML-enhanced ESM components. It supports process-oriented assessment of model performance across atmosphere, ocean, and land domains, while enabling direct comparisons with observational datasets. These methods provide insights into ESM and observation data, facilitating rigorous diagnostics and a deeper understanding of model behavior.

## 🚀 Getting Started

- Browse the available methods.  
- Follow the links to each submodule for setup and usage.  
- Ask the suggested contacts for access to submodules which are currently private.


## 📂 Available Methods

- [Interpretable Analysis of Climate Scenarios Using Dynamic Mode Decomposition with Control](https://github.com/nmank/DMDc4Climate)  
  ![python](https://img.shields.io/badge/python-yellow) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)  [![paper](https://img.shields.io/badge/paper-gray)](https://doi.org/10.1017/eds.2025.8) 
    - [Quickstart](https://github.com/nmank/DMDc4Climate/blob/main/getting_started.ipynb) 

- [Kernel Taylor Diagram for Earth System Model Evaluation](https://github.com/andrei-ml/kernel-taylor-diagram) (contact <andrei.gavrilov@uv.es>)  
  ![python](https://img.shields.io/badge/python-yellow) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)  

  *This repository provides a set of metrics extensions for the Taylor diagram. The classic Taylor diagram allows plotting, in a single graph, the RMSE, correlation between two datasets, and their amplitudes (standard deviations). All these quantities can be derived from the inner product defined for two datasets, X (truth) and Y (tested). Here, we extend this framework by generalizing the inner product based on both classic and kernel metrics, enabling the capture of nonlinear and probabilistic similarity relations between datasets.*

- [Dynamic Mode Decomposition with control for forced response estimation in ESMs](https://github.com/andrei-ml/DMDcForcedResponseEstimation) (contact <andrei.gavrilov@uv.es>)  
  ![python](https://img.shields.io/badge/python-yellow) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)  
 
  *This repository provides the DMDc-p method for estimating forced responses in Earth system models (ESMs) as part of systematic ESM evaluation. It estimates the forced response by computing the pullback attractor of a linear non-autonomous stochastic system, with the DMDc model representing its deterministic core, assumed to approximate the underlying data-generating system. The method is compared against baseline approaches such as linear inverse models (LIM) and linear regression using large ESM ensembles.*


- [DMDc variants for Forced Component Estimation Statistical Method Intercomparison](https://github.com/andrei-ml/DMDcForcedResponseEstimation) (contact <andrei.gavrilov@uv.es>)  
  ![python](https://img.shields.io/badge/python-yellow) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)  

  *This repository contains implementations of 3 different Dynamic Mode Decomposition with control (DMDc)–based methods for estimating the forced response from a single climate realization. These methods were applied within Tiers 2 and 3 of the [Forced Component Estimation Statistical Method Intercomparison Project (ForceSMIP)](https://sites.google.com/ethz.ch/forcesmip).*


- [HybridESMBench: Benchmarking tool for hybrid ESMs](https://github.com/HybridESM/HybridESMBench)  
  ![python](https://img.shields.io/badge/python-yellow) [![License: Apache](https://img.shields.io/badge/License-Apache-yellow.svg)](https://opensource.org/licenses/Apache-2-0) 


- [Structual Causal Model techniques for interpreting model coupling behavior: Causal Land-Atmosphere-Ocean coupling strength](https://github.com/feinihuang9554-max/Causal-strength-for-Land-Atmosphere-Ocean-coupling.git) (contact <feini.huang@uv.es>)  
![python](https://img.shields.io/badge/python-yellow)

- [Joint XAI for nonlinear sensitivity of environmental factors to target: Cloud feedback sensitivity](https://github.com/feinihuang9554-max/Interpretable-CNN-for-nonlinear-sensitivity.git) (contact <feini.huang@uv.es>)  
![python](https://img.shields.io/badge/python-yellow)



## License

Please check out License for each submodule linked in this repository.

---

## 📬 Contact

For questions and contributions, please reach out to the [ISP at UVEG](https://isp.uv.es/):

- Feini Huang  <feini.huang@uv.es>  
- Andrei Gavrilov <andrei.gavrilov@uv.es>  
