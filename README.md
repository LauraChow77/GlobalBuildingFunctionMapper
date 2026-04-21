# GlobalBuildingFunctionMapper

## Overview

Building function information is essential for urban planning and governance, yet fine-grained functional references remain severely incomplete at the global scale. This work presents:

- **Global Building Function (GBF) dataset** — a multilevel dataset constructed from Sentinel-1/2 imagery, topographic data, and OpenStreetMap POIs, with hierarchically nested labels spanning coarse to fine categories
- **A deep learning framework** incorporating a hierarchy-consistent loss (HCL) and a harmonized pseudo-labeling strategy (HPL) to exploit label sparsity across semantic levels

### Hierarchical Classification System

<p align="center">
  <img src="figures/label_system.png" width="80%">
</p>

## Repository Structure

    GlobalBuildingFunctionMapper/
    ├── README.md
    ├── LICENSE
    ├── dataset/        # GBF dataset download links & documentation
    ├── model/          # Pretrained model weights
    └── code/           # Training, inference, and evaluation scripts

## Dataset

The GBF dataset contains **38,528 image patches** (256 × 256 pixels) across six continents, each comprising multimodal physical observations, POI features, and hierarchical labels.

<p align="center">
  <img src="figures/dataset_overview.png" width="80%">
</p>

## Model

Pretrained model weights will be released.

## Code

Source code for training, evaluation, and inference will be released.
