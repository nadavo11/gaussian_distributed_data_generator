# gaussian_distributed_data_generator & plotting 3D data


## Overview

This project is a Python implementation of a clustering algorithm for 3D data. The algorithm uses Gaussian mixture models to cluster data points into groups, with each group represented by a different color in the output visualization. The project includes a function for generating random 3D data points with a specified number of clusters and variance.

## Installation

To use this project, you'll need to have Python 3.x installed on your machine. You can download Python from the official website: https://www.python.org/downloads/

You will also need to install the following dependencies:

- NumPy
- Matplotlib

You can install these dependencies using pip, the Python package installer. Simply run the following command in your terminal or command prompt:
```python
pip install numpy matplotlib

```

## Usage

To use the clustering algorithm, import the `visualize_3D_clusters` function from the `clustering.py` module:

```python
from clustering import visualize_3D_clusters
```
You can then generate a set of random 3D data points using the `generate_gaussian_cluster` function:
