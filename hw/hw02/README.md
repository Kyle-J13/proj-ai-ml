# HW02 – Decision Trees, Bagging, and Boosting

This notebook implements tree based machine learning methods on the HIGGS dataset to classify particle collision events as either signal (Higgs boson) or background.

## Dataset

A cleaned version of the HIGGS dataset is used. Features with high multicollinearity were removed using VIF analysis from HW01.

- Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/280/higgs)
- File: `hw01/data/HIGGS_subset_clean.csv`

## Setup

1. Create the environment:
   ```bash
   conda env create -f environment.yml
