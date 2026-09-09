# NLP Assignments -- Group 48

Coursework for *Natural Language Processing* at Vrije Universiteit Amsterdam, Spring 2025.

## Overview

This repository contains group assignments covering foundational NLP techniques, from statistical language modelling to neural dependency parsing.

## Assignment 2: Language Modelling and Word Vectors (`A2/`)

- **Text processing and Zipf's law** -- frequency analysis on the Brown Corpus, verifying the Zipfian distribution
- **N-gram language modelling** -- unigram, bigram, and trigram models with additive smoothing; text generation from learned distributions
- **Word vectors via co-occurrence statistics** -- building word representations from co-occurrence matrices
- **PMI and PPMI** -- pointwise mutual information for measuring statistical association between words

Key files: `code/problem1.py` (text processing), `code/NLP_A2_final.ipynb` (n-grams and generation), `code/pmi.ipynb` (PMI/PPMI analysis).

## Assignment 4: MLP Classifier and Dependency Parsing (`A4/`)

- **MLP text classifier** -- multi-layer perceptron for text classification (`A4_MLP.ipynb`)
- **Transition-based dependency parsing** -- arc-standard parser with an MLP scoring model, trained and evaluated on CoNLL-format treebanks

Key files: `DepParsing/run.py` (training and evaluation), `DepParsing/parser_model.py` (neural model), `DepParsing/parser_transitions.py` (transition system).

## How to Run

```bash
pip install jupyter numpy matplotlib torch
# Assignment 2
jupyter notebook A2/code/NLP_A2_final.ipynb
# Assignment 4 -- dependency parser
cd A4/NLP_2025_A4/DepParsing
python run.py
```

## Requirements

- Python 3.10+
- Jupyter Notebook
- NumPy, Matplotlib, PyTorch

## Course

Natural Language Processing -- Vrije Universiteit Amsterdam, Spring 2025
