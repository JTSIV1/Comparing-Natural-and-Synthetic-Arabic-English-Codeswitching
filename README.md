# Comparing-Natural-and-Synthetic-Arabic-English-Codeswitching

This repository contains code and data for a project comparing the performance of word embeddings trained on natural and synthetic Arabic-English code-switched text.

## Data

The data used in this project is an [Arabic-English Code-Switching Corpus](https://huggingface.co/datasets/MohamedRashad/arabic-english-code-switching) and a synthetic dataset generated using the [SDAIA ArE-CSTD Dataset](https://huggingface.co/datasets/SDAIANCAI/Ar-En-Code-Switching-Textual-Dataset).

## Code

The code in this repository is written in Python and uses the [Gensim](https://radimrehurek.com/gensim/) library for training word embeddings and the [NLTK](https://www.nltk.org/) library for text processing.

The code is organized into several notebooks:

* `1 explore_models.ipynb`: This notebook contains code for training and evaluating word embeddings on the natural and synthetic datasets.
* `2 get_common_vocab.ipynb`: This notebook contains code which finds the common vocabulary words across each model, allowing for fair analysis later on.
* `3 analyze_results.ipynb`: This notebook contains code for analyzing the results of the evaluation.

To follow along, or run the code yourself, progress through the notebooks in their numbered order.

## Results

The results of the evaluation are presented in the form of tables and plots in the `analyze_results.ipynb` notebook.
