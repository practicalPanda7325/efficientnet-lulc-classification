# EfficientNet-Based LULC Classification

## Overview
This project explores Land Use Land Cover (LULC) classification using EfficientNet 
models on multi-sensor satellite imagery. The focus is on understanding model behavior, 
training dynamics, and performance across different configurations.

## Dataset
- Multi-sensor satellite imagery:
  - PlanetScope (optical)
  - Sentinel-1 (SAR)

- Preprocessing tools:
  - SNAP
  - QGIS

Note: The dataset was provided as part of an academic course and is not publicly available.

## Methodology
- Data preprocessing and patch-based dataset preparation
- Training EfficientNet-based architectures
- Experimentation with different configurations and training strategies
- Analysis of training behavior and performance across runs

## Experiments
The project includes multiple experimental runs to evaluate:

- Model convergence behavior
- Effect of different training configurations
- Performance variations across sensor modalities

All experiments and observations are documented in the notebooks.

## Code Structure
- `notebooks/training.ipynb`  
  Contains the primary training pipeline and model implementation

- `notebooks/experiments.ipynb`  
  Contains additional experiments, variations, and exploratory analysis

## Setup

Install dependencies:

```bash
pip install -r requirements.txt
