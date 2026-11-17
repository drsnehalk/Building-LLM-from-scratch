# Building an LLM from Scratch

A hands-on learning repository for understanding how large language models work by implementing their building blocks in Python and PyTorch. The project follows concepts and exercises from Sebastian Raschka’s book, *Build a Large Language Model (From Scratch)*.

## What’s here

The repository currently contains a Jupyter notebook covering the early data-preparation steps:

- Basic text tokenization and vocabulary construction
- Handling unknown and special tokens
- Byte-pair encoding with the GPT-2 tokenizer from `tiktoken`
- Creating input/target sequences with a sliding window
- Building a PyTorch `Dataset` and `DataLoader` for language-model training

This is a work in progress. More notebooks and model components can be added as the study progresses.

## Getting started

1. Clone the repository and open `Tokenization.ipynb` in Jupyter Notebook, JupyterLab, or Google Colab.
2. Install the dependencies used in the notebook:

   ```bash
   pip install torch tiktoken requests
   ```

3. Run the notebook cells in order. The notebook downloads the sample text `the-verdict.txt` when it is not already present.

A recent Python 3 environment is recommended. PyTorch installation options vary by operating system and hardware; see the [official PyTorch installation guide](https://pytorch.org/get-started/locally/) if the command above does not match your setup.

## Repository structure

```text
.
├── README.md
└── Tokenization.ipynb
```

## Learning reference

This repository is an educational companion to Sebastian Raschka’s book, [*Build a Large Language Model (From Scratch)*](https://www.manning.com/books/build-a-large-language-model-from-scratch). The code and notes here are for learning and experimentation; consult the book and its [official companion repository](https://github.com/rasbt/LLMs-from-scratch) for the complete reference material.

## Disclaimer

This project is independently maintained and is not affiliated with or endorsed by the author or publisher. Please refer to the book and source repository for licensing and attribution details for their materials.
