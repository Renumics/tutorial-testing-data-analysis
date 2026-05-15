# Tutorial: Testing Data Analysis with Machine Learning

Jupyter Notebooks for learning the fundamentals of machine learning in test data analysis — aimed at beginners in Python programming.

## Contents

| Notebook | Domain | Topic |
|----------|--------|-------|
| `audio_classification.ipynb` | Audio | Transformer embeddings + SVM classification on ESC-50 |
| `hf_cifar100.ipynb` | Image | Vision Transformer on CIFAR-100 with embedding visualization |
| `f1_embedding_generation.ipynb` | Time Series | F1 telemetry embeddings with Chronos-2 |

## Prerequisites

- Python 3.12
- 16 GB RAM recommended
- Internet access for initial download of datasets and models

## Installation

Extract the zip archive and install the dependencies:

### Linux

```bash
unzip tutorial-testing-data-analysis.zip
cd tutorial-testing-data-analysis
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

### Windows

```bash
unzip tutorial-testing-data-analysis.zip
cd tutorial-testing-data-analysis
python -m venv .venv
.\.venv\Scripts\Activate
pip install -r requirements.txt
```

## Getting Started

```bash
jupyter lab
```

Or use any editor with Jupyter support (VS Code, Cursor, etc.).
