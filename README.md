# Applied Statistics

This repository contains my coursework for the **Applied Statistics** module, completed as part of the Higher Diploma in Computing in Data Analytics.

The project explores statistical concepts and methods through practical data analysis using Python and Jupyter Notebook.

## Project Overview

The assignment uses the **Iris dataset**, containing measurements of 150 iris flowers across three species: *setosa*, *versicolor*, and *virginica*.

The analysis is divided into four problems:

1. **Exploring Petal Length:** Examining distributions using histograms, descriptive statistics, and fitted normal distributions.
2. **Correlation Analysis:** Investigating the relationship between petal length and petal width using Pearson's correlation coefficient and scatter plots.
3. **Independent-Samples t-Tests:** Comparing petal measurements between pairs of species to assess statistically significant differences.
4. **One-Way ANOVA:** Comparing mean petal measurements across all three species and examining the limitations of multiple pairwise tests.

Each problem includes Python code, visualisations, statistical results, and interpretations.

## Technologies Used

- Python
- Jupyter Notebook
- NumPy
- pandas
- Matplotlib
- Seaborn
- SciPy

## Repository Structure

```

├── problems.ipynb      # Main assignment notebook
├── requirements.txt    # Python dependencies
├── AGENTS.md           # Project guidance
├── .gitignore          # Excluded files
└── README.md           # Project documentation
```

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/USERNAME/REPOSITORY.git
cd REPOSITORY
```

Replace `USERNAME` and `REPOSITORY` with the appropriate GitHub details.

### 2. Install dependencies

Ensure Python and pip are installed, then run:

```bash
pip install -r requirements.txt
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook problems.ipynb
```

Run the notebook cells sequentially to reproduce the analysis.

## Dataset

The Iris dataset contains 150 observations, with 50 flowers from each species. Each observation includes four numerical measurements:

- Sepal length (cm)
- Sepal width (cm)
- Petal length (cm)
- Petal width (cm)

The dataset is sourced from the [Seaborn Data repository](https://raw.githubusercontent.com/mwaskom/seaborn-data/master/iris.csv).


