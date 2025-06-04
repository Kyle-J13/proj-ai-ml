# Higgs Boson Classification with linear regression

This notebook implements logistic regression on the HIGGS dataset to classify particle collision events as either signal (Higgs boson) or background.

## Dataset

The HIGGS dataset contains 11 million rows and 28 features.  

- Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/280/higgs)
- File: `..data/HIGGS.csv.gz` (not included in repo for size reasons)

## Setup

1. Create the environment:
   ```bash
   conda env create -f environment.yml
