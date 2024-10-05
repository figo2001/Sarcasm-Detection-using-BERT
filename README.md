# Sarcasm Detection Using Hierarchical BERT

This repository contains a project for detecting sarcasm in text using a hierarchical BERT model.

## Project Overview

This project is designed to detect sarcasm in text data, utilizing a hierarchical BERT architecture. Sarcasm detection is a complex natural language processing task due to the nuanced nature of sarcasm, and this model aims to address these challenges effectively.

## Notebooks

The main project is organized within a Jupyter Notebook that includes:

- **Data preprocessing**: The steps to prepare and clean text data.
- **Model training**: Hierarchical BERT implementation for sarcasm detection.
- **Evaluation**: Methods to assess model performance.

## Installation

To run this project, clone the repository and install the necessary dependencies. This project uses Python and several libraries like TensorFlow, PyTorch, and pandas.

```bash
git clone <repository-url>
cd sarcasm-detection-using-hierarchical-bert
pip install -r requirements.txt
```

## Usage

After installing the dependencies, you can run the notebook:

```bash
jupyter notebook sarcasm-detection-using-hierarchical-bert.ipynb
```

## Dependencies

- pandas
- TensorFlow
- PyTorch
- scikit-learn
- numpy
- transformers

## Model Description

The model utilizes BERT (Bidirectional Encoder Representations from Transformers) in a hierarchical setup to capture contextual information for detecting sarcasm in text.

## Results

The model's performance metrics will be displayed after training, including accuracy, precision, recall, and F1-score.
