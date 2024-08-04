# Anomaly Detection

This repository contains the implementation of anomaly detection in network latency and throughput data using Gaussian distribution and contour plots.

## Overview

The project visualizes a dataset of network latency and throughput measurements, fits a Gaussian distribution to the data, and identifies anomalies based on the distribution. The main components of the project include:
- Plotting the dataset
- Fitting a Gaussian distribution
- Visualizing the distribution with contour plots
- Identifying and highlighting anomalies

## Files

- `C3_W1_Anomaly_Detection.ipynb`: Jupyter notebook with the implementation of the anomaly detection algorithm.
- `figure1.png`: Scatter plot of the dataset.
- `figure2.png`: Gaussian distribution contours fitted to the dataset.
- `figure3.png`: Anomalies classified and highlighted on the contour plot.
- `public_tests.py`: Public tests for the functions used in the project.
- `utils.py`: Utility functions for the project.

## Installation

To run the notebook and reproduce the results, ensure you have the following dependencies installed:
- Python 3.x
- NumPy
- Matplotlib
- Jupyter

You can install the required packages using pip:

pip install numpy matplotlib jupyter

## Usage

1. Clone the repository:

git clone https://github.com/regmibhuwan/anomaly-detection.git

2. Navigate to the project directory:

cd anomaly-detection

3. Open the Jupyter notebook:

jupyter notebook C3_W1_Anomaly_Detection.ipynb

4. Run the cells in the notebook to see the implementation and results.

## Figures
- Figure 1: Scatter plot of the dataset.
- Figure 2: Gaussian distribution contours fitted to the dataset.
- Figure 3: Anomalies classified and highlighted on the contour plot
