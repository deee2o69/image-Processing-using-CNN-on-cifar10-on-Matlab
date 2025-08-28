# Image Processing with CNN on CIFAR-10 Using MATLAB

*(Repository authored by deee2o69)*

##  Overview

This project explores image classification on the CIFAR-10 dataset using Convolutional Neural Networks (CNN) in MATLAB. It includes several neural network architectures implemented via MATLAB Live Scripts (`.mlx`), varying in depth and complexity. Features:

- Live scripts for different network configurations: 2-layer, 3-layer, 4-layer, 5-layer, and 9-layer CNNs.
- A main execution script (`Main.mlx`) to orchestrate training and evaluation over multiple configurations.
- Scripts for loading and preprocessing the CIFAR-10 data (`loadtrainingdata.mlx`).
- Experimentation and configuration via `testconfigs.mlx`, `createTrainingOptions.mlx`.
- Results aggregation and visualization scripts (`aggregate_results.mlx`, `Scattergraph.mlx`).
- Performance reporting: `Best Result`, `Test Output`, plus visual summaries like `35 layers.png`, `summary.png`.
- An Excel summary of experiments (`experiment_summary.xlsx`).

##  Repository Structure

```text
├── Main.mlx
├── loadtrainingdata.mlx
├── createTrainingOptions.mlx
├── testconfigs.mlx
├── conv2layers.mlx
├── conv3layers.mlx
├── conv4layers.mlx
├── conv5layers.mlx
├── conv9layers.mlx
├── aggregate_results.mlx
├── Scattergraph.mlx
├── experiment_summary.xlsx
├── 35 layers.png
├── summary.png
├── Best Result
├── Test Output
└── cifar-10-batches-mat/   (CIFAR-10 data files)
