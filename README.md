# Deep Learning for Natural Language Processing

Coursework and experiments for a Deep Learning for Natural Language Processing course. The repository studies sentiment classification for tweets through exploratory data analysis, text preprocessing, feature engineering, and deep learning models.

## Contents

| Notebook | Focus |
| --- | --- |
| [`homework_1.ipynb`](homework_1.ipynb) | Tweet exploration, preprocessing, TF-IDF feature extraction, and baseline model experiments |
| [`homework_2.ipynb`](homework_2.ipynb) | Reproducible sentiment experiments with additional preprocessing and PyTorch models |
| [`homework_3_1.ipynb`](homework_3_1.ipynb) | BERT-based tweet sentiment classification |
| [`homework_3_2.ipynb`](homework_3_2.ipynb) | Additional Homework 3 model experiments and evaluation |

The [`assignments/`](assignments/) directory contains the original homework briefs. Supporting task documentation is available in [`docs/`](docs/).

## Topics Covered

- Exploratory analysis of positive and negative tweet datasets
- Tweet length, word-frequency, n-gram, and word-cloud analysis
- Text normalization, contraction expansion, lemmatization, slang conversion, and anonymization of mentions and email addresses
- Stop-word filtering comparisons
- TF-IDF feature extraction and hyperparameter tuning
- Neural sentiment classification with PyTorch
- BERT fine-tuning and evaluation
- Reproducible experiments using fixed random seeds

## Requirements

- Python 3.10 or newer
- Jupyter Notebook or JupyterLab
- A working PyTorch installation; a CUDA-capable GPU is recommended for the BERT notebooks

The notebooks include package installation and import cells. Review those cells before running them, especially when selecting a PyTorch build for your operating system and hardware.

## Getting Started

1. Clone the repository and enter its directory:

	```bash
	git clone https://github.com/Aggelos561/nlp-projects.git
	cd nlp-projects
	```

2. Create and activate a virtual environment:

	```bash
	python -m venv .venv
	source .venv/bin/activate
	```

3. Start Jupyter:

	```bash
	jupyter lab
	```

4. Open the notebooks in numerical order. The notebooks expect the relevant train, validation, and test CSV datasets to be available at the paths configured in their data-loading cells.

## Reproducibility

Homework 2 and Homework 3 explicitly seed the Python, NumPy, and PyTorch random-number generators. Exact results may still vary across hardware, library versions, and CUDA settings.

## Academic Note

This repository is published as a record of coursework and learning experiments. If you are taking the same course, use it to understand the methods rather than submitting the work as your own.
