# neuralnetworkbasedcompiler_DL
This project aims to investigate the use of machine learning models to automatically predict  compiler optimization levels. The study focuses on extracting key static features from source  code to serve as inputs to a model, which can then predict one of the four predefined  optimization levels.
Specifically, we extract three static code features: loop count, branch count, and memory-access count. These features are computed for 2,500 distinct code snippets, which represent a diverse range of code structures and patterns. These snippets are then used as the training data to develop predictive models capable of selecting the optimal optimization level for each code sample.

# Neural Network-Based Compiler

This project implements a **compiler front-end powered by neural networks** using Python and deep learning. It replaces traditional lexical and syntactic analysis with a trained model capable of predicting and classifying source code tokens.

---

# Overview

- Built with Python and Jupyter Notebooks.
- Uses **RNN / GRU / Transformer-based** architectures for token classification and syntax modeling.
- Designed to handle and interpret code as sequences — similar to how NLP handles language.
- Applies deep learning to simulate parts of the compiler pipeline.

---

# Files Included

| File Name         | Description                                                  |
|-------------------|--------------------------------------------------------------|
| `phase_1.ipynb`   | Tokenization & lexical preprocessing of source code.         |
| `phase_2.ipynb`   | Neural network model training and evaluation.                |
| `phase-3.ipynb`   | Source code prediction and compilation output generation.    |

---

# How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/neural-compiler.git
   cd neural-compiler
