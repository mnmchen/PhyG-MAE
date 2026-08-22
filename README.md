# Supplemental Materials for PhyG-STMAE

This repository provides the supplemental materials associated with the manuscript:

> **Physics-Informed Graph Masked Autoencoder for Spatiotemporal Wind Pressure Imputation and Sensor Placement Optimization**

**Authors:** Xue Li, Peize Li, Lixiao Li, Yingwu Zhou, Feng Xing, and Cheng Chen\*

\*Corresponding author: [cchen@jnu.edu.cn](mailto:cchen@jnu.edu.cn)

## Overview

The study presents a Physics-Informed Graph Spatiotemporal Masked Autoencoder (PhyG-STMAE) for two closely related civil-engineering sensing tasks:

1. reconstructing full-field wind-pressure responses from a small subset of healthy sensors; and
2. identifying compact and informative sensor layouts without retraining the imputation model.

PhyG-STMAE incorporates sensor coordinates, wind-profile information, structural aspect ratio, and wind direction into a graph-enhanced masked autoencoder. Distance-weighted graph aggregation captures local geometric relationships, while spatial and temporal Transformer modules learn long-range dependencies in wind-pressure fields.

The framework is validated using wind-tunnel pressure measurements for an NACA 4415 airfoil and high-rise building models.

## Supplemental Materials

This repository contains supporting materials that cannot be presented effectively in the main manuscript because of figure and page limitations, including:

- additional reconstruction results;
- supplementary figures and tables;
- full spatiotemporal pressure-reconstruction animations;
- representative measured and imputed pressure-field comparisons;
- sensor-retention and placement-optimization results; and
- documentation associated with the validation cases.

The static key frames presented in the manuscript are complemented here by the corresponding full animations.

## Code Availability

The source code used for data preprocessing, model training, pressure-field imputation, sensor-retention analysis, and greedy sensor placement optimization is not included in the initial repository release.

To support the continuing development, verification, and documentation of the research software, the complete implementation is planned to be made publicly available **one year after the official publication date of the paper**.

The repository will be updated when the code is released. The future code release is expected to include:

- spatial and spatiotemporal model implementations;
- training and validation scripts;
- dynamic masking procedures;
- graph construction and physics-informed feature processing;
- greedy backward elimination for sensor optimization;
- figure and animation generation scripts; and
- instructions for reproducing the principal results.

## Data Availability

The validation studies use wind-tunnel pressure datasets obtained from their respective data providers. Redistribution and reuse of the original experimental data remain subject to the terms and policies of those providers.

This repository primarily distributes the supplemental results generated in the present study. Detailed data sources and preprocessing procedures are described in the manuscript and its supplemental documentation.

## Citation

The manuscript is currently undergoing publication processing. Citation information will be updated after publication.

```bibtex
@article{Li_PhyGSTMAE,
  title   = {Physics-Informed Graph Masked Autoencoder for Spatiotemporal Wind Pressure Imputation and Sensor Placement Optimization},
  author  = {Li, Xue and Li, Peize and Li, Lixiao and Zhou, Yingwu and Xing, Feng and Chen, Cheng},
  journal = {Journal of Computing in Civil Engineering},
  year    = {forthcoming}
}
