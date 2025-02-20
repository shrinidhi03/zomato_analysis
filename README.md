# zomato_analysis
# Zomato Restaurant Data Analysis

This repository contains a Python/JupyterLab project analyzing Zomato restaurant data to understand trends and restaurant usage.

## Overview

This project explores a Zomato dataset to identify popular cuisines, understand the relationship between restaurant features (cost, location, ratings), and analyze general usage patterns.

Technologies Used

Python
NumPy
Pandas
Matplotlib
Seaborn

## Contents

*   `zomato project.ipynb`: Jupyter Notebook with the analysis
*   `data/`:  Zomato data
*   `README.md`: This file.

## Getting Started

1.  **Clone:** `git clone [your-repo-url]`
2.  **Anaconda Environment (Recommended):**
    ```bash
    conda env create -f environment.yml  
    conda activate zomato_env       
    ```
    Create `environment.yml` with:
    ```yaml
    name: zomato_env
    channels:
      - conda-forge
      - defaults
    dependencies:
      - python=3.9 # Or your Python version
      - pandas
      - matplotlib
      - seaborn
      - jupyterlab
      # Add other packages here
    ```
4.  **Run:** `jupyter lab zomato_analysis.ipynb`

## Analysis

The notebook covers data cleaning, EDA, and analysis of restaurant trends.

## Contributing

Contributions are welcome!
