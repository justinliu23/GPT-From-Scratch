# GPT-From-Scratch

This repository contains an exploration of the fundamental components of Generative Pre-trained Transformers (GPTs), focusing on the core building blocks of large language models.

------

## Overview

This project explored the key elements of GPTs, including:
- **Self-attention**: Mechanisms to determine token-to-token relationships.
- **Positional encoding**: Adding order information to input tokens.
- **Masking**: Enforcing autoregressive token prediction.
- **Transformer blocks**: Stacking multi-head self-attention layers with feed-forward networks.
- **AdderGPT**: A minimal GPT model trained to accurately simulate three-digit addition.

---

## Features

- **`gpt_from_scratch.ipynb`**: A notebook that walks through:
  1. Building and training a simplified GPT from scratch.
  2. Visualizing self-attention and token interactions.
  3. Training AdderGPT to solve addition problems.

- **Visualization**: Attention patterns are plotted to showcase how the model learns to focus on specific tokens.

---

## Usage

### Setup
To get started, ensure you have the following installed:

#### Requirements
- Python 3.8 or higher
- PyTorch
- Matplotlib (for visualizations)

#### Installation
Install the required dependencies using `pip install torch matplotlib jupyter`.

### Running the Notebook
To run the project:
- Open `gpt_from_scratch.ipynb` in Jupyter or Google Colab.
- Follow the step-by-step implementation and training of AdderGPT.
