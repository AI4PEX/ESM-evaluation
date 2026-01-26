# XAI-Causality-for-evaluation
ML4ESM Evaluation Diagnostics
This repository provides machine learning-based evaluation tools for Earth System Models, developed under WP4 of the AI4PEX project.

# Overview
The codebase implements state-of-the-art explainable AI (xAI) and causal discovery methods for evaluating ML-enhanced Earth system model components. These diagnostics enable process-oriented assessment of model performance across atmosphere, ocean, and land domains.


# WP4 ESM evaluation

## Key Features

### Structual Causal Model techniques for interpreting model coupling behavior 
- [Causal Land-Atmosphere-Ocean coupling strength](https://github.com/feinihuang9554-max/Causal-strength-for-Land-Atmosphere-Ocean-coupling.git)

### Joint XAI for nonlinear sensitivity of environmental factors to target
- [Cloud feedback sensitivity](https://github.com/feinihuang9554-max/Interpretable-CNN-for-nonlinear-sensitivity.git)


### Upcoming
- Causal discovery methods to identify bias sources and key drivers
- Representation learning for comparative model evaluation
Process-specific diagnostics for:
- Subtropical low-cloud feedbacks (atmosphere)
- Ocean heat and carbon uptake (ocean)
- Terrestrial water-carbon processes (land)

### Applications
- Compare ML-enhanced ESM prototypes against standard configurations
- Evaluate ML-based parameterizations from WP2 developments
- Analyze cloud radiative feedbacks, ocean eddy parameterizations, and land surface processes
- Support implementation in ESMValTool via WP8 integration

### Development
This work is led by METO and UVEG, with contributions from multiple partners including MPG-BGC, ULUND, DLR, UNIL, UREAD, and UNIVLEEDS. The tools are designed to advance the model evaluation cycle using cutting-edge AI methods.
