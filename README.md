## Overview

The project demonstrates an entropy-based approach for assessing microsatellite instability at the level of individual STR loci, supporting both single-sample and batch classification.

The full methodological description, context, and step-by-step analysis are provided in the main Jupyter notebook:
**MSI_Analysis_Pipeline.ipynb**

## Data
Due to ethical and data protection considerations, the pipeline is demonstrated on a limited example dataset (`example_STRs_MSS_MSI.xlsx`), and STR identifiers are anonymized.

## Requirements

The analysis is implemented in Google Colab.

The following Python packages are used:
- pandas
- numpy
- matplotlib
- scipy
- scikit-learn
- adjustText

The `adjustText` package is installed within the notebook using `pip`.
