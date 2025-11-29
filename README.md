# Drug-Likeness_Calculator

## Overview
A computational tool for early-stage drug screening that evaluates molecules against established medicinal chemistry criteria (Lipinski, Ro3, Veber, Ghose) and predicts aqueous solubility using machine learning. 

## Features
- **Multi-rule screening**: Evaluates molecules against Lipinski Ro5, Rule of 3, Veber, and Ghose filters
- **Solubility Prediction**: Graph Convolutional Network trained on Delaney dataset
- **Integrated Assessment**: Combines rule-based and ML predictions into actionable recommendations

## Technologies
- Python 3.9
- RDKit 2025.09.2
- DeepChem 2.8.1

## Performance
Training R²: 0.91
Test R²: 0.66

## Acknowledgements
GNN implementation adapted from examples in *Deep Learning for the Life Sciences* (Ramsundar et al., O'Reilly 2019). The calculator framework and multi-rule integration are original work.
