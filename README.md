# Failure-analysis-of-parameter-induced-simulation-crashes-in-climate-models

Link to [source code](https://colab.research.google.com/drive/197jHOwPBsezfwU5O61WEuP6-fG7V7Abi#scrollTo=5PPN6b8eAWoX) in Google Colab.

# Data

This dataset contains records of simulation crashes encountered during climate model uncertainty quantification (UQ) ensembles.

The dataset includes 21 columns where:
   - Column 1: Latin hypercube study ID (study 1 to study 3).

   - Column 2: Simulation Crashes ID (run 1 to run 180).

   - Columns 3-20: values of 18 climate model parameters scaled in the interval [0, 1]. These are features impacting on outcomes.

   - Column 21: Simulation Outcome (0 = failure, 1 = success).

You can visit the [Data Source](https://archive.ics.uci.edu/ml/datasets/climate+model+simulation+crashes) here.

# GOAL

- 1st Goal: Understand the concepts of variance and covariance and the math theory behind them.

- 2nd Goal: Understand the basic concepts of eigenvector, eigenvalues and Principle Components Analysis and implement in python language.

# Lab 1 - 2:

- Find probability distribution function (PDF): Uniform PDF with F(x) = 1 for 0 <= x <= 1.

- Understand to generate moment and central moment.

Link the [source code](https://colab.research.google.com/drive/1cefqX1UzfSJUPnBzyh2DK6rjYApuvXHr#scrollTo=ICaG9FEfUQLm) in Google Colab.

# References

[1] https://gmd.copernicus.org/preprints/6/585/2013/gmdd-6-585-2013.pdf

[2] https://vitalflux.com/eigenvalues-eigenvectors-python-examples/

[3] https://machinelearningmastery.com/feature-selection-machine-learning-python/
