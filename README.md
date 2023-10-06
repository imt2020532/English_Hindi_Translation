# English_Hindi_Translation
English Hindi Translation by fine tuning google mt5-small.

# Fine-Tuning Google MT5-Small for English-Hindi Translation

## Overview

This repository contains code and instructions for fine-tuning the Google MT5-Small model for English-Hindi translation using PyTorch and the MT5Tokenizer. By following the steps outlined below, you can adapt the pre-trained model to perform high-quality translation tasks specific to English and Hindi languages.

## Prerequisites

Before proceeding, make sure you have the following prerequisites installed:

- Python (3.7 or higher)
- PyTorch (1.6 or higher)
- Transformers library (Hugging Face Transformers)
- MT5Tokenizer

You can install these dependencies using pip:

```bash
pip install torch transformers
pip install sentencepiece  # For MT5Tokenizer

## Datasets Used

- [English-Hindi Dataset-IIT Bombay](https://www.kaggle.com/datasets/vaibhavkumar11/hindi-english-parallel-corpus): For this example, we will use the IIT Bombay English-Hindi Parallel Corpus dataset.
