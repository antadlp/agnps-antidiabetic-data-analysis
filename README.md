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
- mpl_toolkits
- scikit-learn
- scikitplot

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

- All analyses were performed in Python 3.11.

## Citation

If you use this repository or its results in your work, please cite the following manuscript:

```bibtex
@article{VeraPineda2025,
  title        = {Argovit™ Silver Nanoparticles as a Potent and Multifunctional Alternative to Conventional Antidiabetic Therapies},
  author       = {Vera Pineda, Victoria and Alvarez de la Paz, Antonio and Bogdanchikova, Nina and Pestrykov, Alexey and Acevedo Fernández, Juan José and Segura Campos, Maira Rubi},
  journal      = {To be updated},
  year         = {2025},
  note         = {Manuscript in preparation},
  affiliation  = {1 Facultad de Ingeniería Química, Universidad Autónoma de Yucatán, Mérida, México; 
                   2 Instituto de Investigaciones en Materiales, Universidad Nacional Autónoma de México, México D.F., México; 
                   3 Centro de Nanociencias y Nanotecnología, Universidad Nacional Autónoma de México, Ensenada, BC, México; 
                   4 Research School of Chemistry \& Applied Biomedical Sciences, Tomsk Polytechnic University, Tomsk, Russia; 
                   5 Facultad de Medicina, Universidad Autónoma del Estado de Morelos, Cuernavaca, Morelos, México; 
                   6 Facultad de Ingeniería Química, Universidad Autónoma de Yucatán, Mérida, México},
  orcid        = {0000-0002-9511-5673, 0000-0001-7316-4186, 0000-0003-0929-3535, 0000-0002-9034-4733, 0000-0001-8306-1690, 0000-0002-7664-6647}
}
```

---
© 2025 Authors of the manuscript. Licensed for academic and research use.