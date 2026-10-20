
# ESM Evaluation Diagnostics

This repository provides machine learning-based evaluation tools for Earth System Models (ESMs), developed under WP4 of the AI4PEX project.

The codebase implements state-of-the-art explainable AI (XAI), causal discovery, and data-driven interpretable analysis methods for evaluating ML-enhanced ESM components. It supports process-oriented assessment of model performance across atmosphere, ocean, and land domains, while enabling direct comparisons with observational datasets. These methods provide insights into ESM and observation data, facilitating rigorous diagnostics and a deeper understanding of model behavior.

## 🚀 Getting Started

- Browse the available methods.  
- Follow the links to each submodule for setup and usage.  
- Some submodules are kept private until method publication. We encourage you to ask for access to them by contacting the assosiated author.


## 📂 Available Methods

- [Analysis of Climate Scenarios Using Dynamic Mode Decomposition with Control](https://github.com/nmank/DMDc4Climate)  
  ![python](https://img.shields.io/badge/python-yellow) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)  [![paper](https://img.shields.io/badge/paper-gray)](https://doi.org/10.1017/eds.2025.8) 
    - [Quickstart](https://github.com/nmank/DMDc4Climate/blob/main/getting_started.ipynb) 

- [Pullback DMDc for Disentangling Forced Response and Internal Variability in ESMs](https://github.com/IPL-UV/PullbackDMDc)   
  ![python](https://img.shields.io/badge/python-yellow) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![paper](https://img.shields.io/badge/paper-gray)](https://doi.org/10.48550/arXiv.2607.18298) 
  - [Quickstart](https://github.com/IPL-UV/PullbackDMDc/blob/main/getting_started_pullbackdmdc.ipynb)

- [DMDc variants for Forced Component Estimation Statistical Method Intercomparison](https://github.com/andrei-ml/dmdc-forcesmip)   
  ![python](https://img.shields.io/badge/python-yellow) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![paper(Tier1)](https://img.shields.io/badge/paper-Tier1-yellow)](https://doi.org/10.1175/JCLI-D-25-0326.1)
  - [Quickstart](https://github.com/andrei-ml/dmdc-forcesmip/blob/main/demo_evaluation_results.ipynb)  

- [Causal Model Weighting](https://github.com/vdeltatto/climwip-crps)  
  ![python](https://img.shields.io/badge/python-yellow)
  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)  

- [Kernel Taylor Diagram for Earth System Model Evaluation](https://github.com/andrei-ml/kernel-taylor-diagram) (contact <andrei.gavrilov@uv.es>)  
  ![python](https://img.shields.io/badge/python-yellow) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)  

  *This repository provides a set of metrics extensions for the Taylor diagram. The classic Taylor diagram allows plotting, in a single graph, the RMSE, correlation between two datasets, and their amplitudes (standard deviations). All these quantities can be derived from the inner product defined for two datasets, X (truth) and Y (tested). Here, we extend this framework by generalizing the inner product based on both classic and kernel metrics, enabling the capture of nonlinear and probabilistic similarity relations between datasets.* 

- [HybridESMBench: Benchmarking tool for hybrid ESMs](https://github.com/HybridESM/HybridESMBench)  
  ![python](https://img.shields.io/badge/python-yellow) [![License: Apache](https://img.shields.io/badge/License-Apache-yellow.svg)](https://opensource.org/licenses/Apache-2-0) 


- [Structual Causal Model techniques for interpreting model coupling behavior: Causal Land-Atmosphere-Ocean coupling strength](https://github.com/feinihuang9554-max/Causal-strength-for-Land-Atmosphere-Ocean-coupling.git) (contact <feini.huang@uv.es>)  
  ![python](https://img.shields.io/badge/python-yellow)

  *This repository provides a machine-learning and causal-inference framework to quantify land–ocean–atmosphere (LOA) coupling in the Earth system. The method integrates ML emulators, explainable AI (XAI), and structural causal models (SCMs) to move beyond correlation-based diagnostics and enable causal, process-level analysis of Earth system interactions.*

- [Joint XAI for nonlinear sensitivity of environmental factors to target: Cloud feedback sensitivity](https://github.com/feinihuang9554-max/Interpretable-CNN-for-nonlinear-sensitivity.git) (contact <feini.huang@uv.es>)  
  ![python](https://img.shields.io/badge/python-yellow)

  *This repository presents a nonlinear, data-driven framework to quantify the sensitivity of shortwave cloud feedback to cloud-controlling factors (CCFs) when cloud feedback is represented using kernel-weighted cloud property histograms. The method combines convolutional neural networks (CNNs) with explainable artificial intelligence (XAI) to diagnose nonlinear, state-dependent cloud–environment interactions that cannot be captured by traditional linear regression approaches.*




## License

Please check out License for each submodule linked in this repository.

---

## 📬 Contact

For questions and contributions, please reach out to the [ISP at UVEG](https://isp.uv.es/):

- Feini Huang  <feini.huang@uv.es>  
- Andrei Gavrilov <andrei.gavrilov@uv.es>  
