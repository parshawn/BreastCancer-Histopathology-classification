# Deep Learning for Histopathology Image Classification

This repository contains the codebase for a convolutional neural network (CNN)-based classification pipeline applied to histopathology images. The objective of the project is to evaluate the performance of models such as ResNet18 and ResNet50 in classifying pathology image tiles. The experiments examine how factors like transfer learning, layer freezing, and data augmentation affect model performance in terms of precision, macro-F1 score, and validation loss.

## Project Overview

- Multi-class classification of histopathology images (e.g., tumor subtypes)
- Comparison of ResNet18 and ResNet50 architectures
- Evaluation of frozen versus unfrozen layer configurations
- Use of standard performance metrics, including macro-F1 score, precision, recall, and loss curves
- Implementation of K-Fold cross-validation to improve generalization
- Custom training and evaluation pipelines in PyTorch

## Directory Structure

This repository contains the following key files:

- `Histopathology_Classification.ipynb` — Main Jupyter notebook implementing the CNN-based classification pipeline, including data loading, preprocessing, model training, evaluation, and result visualization.

- `README.md` — This file, which provides an overview of the project, setup instructions, and key components.

- `requirements.txt` — List of Python packages required to run the notebook (e.g., PyTorch, NumPy, Pandas, scikit-learn, Matplotlib).

- `.gitignore` — Specifies files and directories to exclude from version control, such as Jupyter checkpoints and Python bytecode.


## Dataset Instructions

This project uses the **Breast Histopathology Images** dataset from Zenodo:

**Download link:** [https://zenodo.org/records/3632035](https://zenodo.org/records/3632035)

Due to storage limitations, the dataset is not included in this repository.

### How to Download

1. Go to the dataset page on Zenodo: [https://zenodo.org/records/3632035](https://zenodo.org/records/3632035)
2. Download and extract the ZIP file(s) containing image tiles.
3. Organize the extracted folders into the following structure:

## Installation

Clone the repository and install the required dependencies:

```bash
git clone https://github.com/your-username/histopathology-cnn-classifier.git
cd histopathology-cnn-classifier
pip install -r requirements.txt
