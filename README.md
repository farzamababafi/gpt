# GPT from Scratch

This repository contains a single Jupyter notebook, `gpt_dev.ipynb`, that builds a simple GPT-style language model from scratch using PyTorch.

## Contents

- `gpt_dev.ipynb` - interactive notebook containing the full walkthrough.
- `input.txt` - the Tiny Shakespeare dataset downloaded by the notebook when executed.

## What this project does

The notebook demonstrates:

- downloading and inspecting the Tiny Shakespeare dataset
- building character-level tokenization and encoding
- preparing training and validation batches
- implementing a simple bigram language model
- training the model with PyTorch
- generating new text from the trained model
- explaining the mathematical intuition behind self-attention
- implementing a full transformer-style GPT model with multi-head attention

## Requirements

- Python 3.8+
- PyTorch
- Jupyter Notebook or JupyterLab
- `wget` (optional, the notebook downloads the dataset automatically)

## Setup

1. Create a virtual environment (recommended):

```bash
python -m venv .venv
source .venv/bin/activate
```

2. Install dependencies:

```bash
pip install torch jupyter
```

3. Open the notebook:

```bash
jupyter notebook gpt_dev.ipynb
```

Or open `gpt_dev.ipynb` in VS Code directly.

## Usage

- Run the notebook cells sequentially.
- The first cell downloads the tiny Shakespeare dataset and saves it to `input.txt`.
- Later sections build, train, and sample from the model.
- The final notebook section contains a complete finished GPT implementation for reference.

## Notes

- The notebook is intended for learning and experimentation rather than production use.
- It uses a small dataset and a compact model to keep training fast and easy to follow.
- If CUDA is available, the notebook will use it automatically for training.

## License

No license is specified. Feel free to use and adapt the notebook for educational purposes.
