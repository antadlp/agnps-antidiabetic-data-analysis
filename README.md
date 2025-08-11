# AgNPs Antidiabetic Data Analysis

This repository contains part of the data analysis for the manuscript entitled *"Argovit™ Silver Nanoparticles as a Potent and Multifunctional Alternative to Conventional Antidiabetic Therapies"*.

## Requirements

This project requires the following Python libraries:

- matplotlib
- networkx
- numpy
- pandas
- scipy
- seaborn

## Installation

It is recommended to use [conda](https://docs.conda.io/) to create an isolated environment:

```bash
# Create a new conda environment with Python 3.11
conda create -n agnps-analysis python=3.11

# Activate the environment
conda activate agnps-analysis

# Install required packages
pip install -r requirements.txt
```

Alternatively, you can install the packages manually:

```bash
pip install matplotlib networkx numpy pandas scipy seaborn
```

## Usage

1. Clone this repository:

```bash
git clone https://github.com/yourusername/AgNPs-antidiabetic-analysis.git
cd AgNPs-antidiabetic-analysis
```

2. Activate your conda environment.

3. Open and run the Jupyter Notebook:

```bash
jupyter notebook "Correlation network analysis.ipynb"
```

## Notes

- The final figure in the manuscript was manually edited to remove specific connections between the features.
- All analyses were performed in Python 3.11.

---
© 2025 Authors of the manuscript. Licensed for academic and research use.
