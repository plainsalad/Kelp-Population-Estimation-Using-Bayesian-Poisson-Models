# Kelp Popoulation Estimation Using Bayesian Poisson Models

This project involves fitting discrete and multi-level models to a dataset of kelp plant counts near the coast. The coastal area is divided into grid squares, and the goal is to estimate the number of kelp in the missing cells.

## Files

- `Code.ipynb`
- `kelp_data.csv` (assuming the data is in a CSV file, adjust as needed)

## Requirements

- Python 3.x
- Matplotlib
- NumPy

## Installation

1. Clone the repository or download the files.
2. Install the required libraries using pip:

    ```sh
    pip install matplotlib numpy
    ```

## Usage

### Running the Analysis

1. Open the `Code.ipynb` notebook using Jupyter Notebook or JupyterLab.
2. Run all the cells to perform the analysis. The notebook will:
    - Load and visualize the dataset.
    - Fit discrete and multi-level models to the data.
    - Estimate the number of kelp in the missing cells.
    - Visualize the results.

## Dataset

The dataset used in this project consists of kelp plant counts in a coastal area. The area is divided into 100 20 m × 20 m grid squares. Some grid squares have missing data.

### Key Variables

- **Kelp Count**: The number of kelp plants in each grid square.
- **Grid Coordinates**: The x and y coordinates of each grid square.

## Code Explanation

### Code.ipynb

This Jupyter notebook performs the following steps:

- **Data Loading**: Loads the dataset and inspects the initial structure.
- **Data Visualization**: Plots the kelp counts in each grid cell, highlighting missing data.
- **Model Fitting**: Fits discrete and multi-level models to the data.
- **Estimation**: Estimates the number of kelp in the missing grid cells.
- **Result Visualization**: Visualizes the estimated kelp counts.

## Conclusion

The project aims to provide accurate estimates of kelp counts in the missing grid cells using discrete and multi-level models.
