# Kotha-S1 Notebook

This repository contains the training, fine-tuning, and inference code for Kotha-S1, a bilingual (Bengali and English) language model.

## Overview
- Architecture: LLaMA-like (RMSNorm + RoPE + SwiGLU)
- Parameters: ~100M
- Context Length: 512
- Tokenizer: Custom Byte-level BPE (32,000 vocab size)

## Contents
- `kotha-s1.ipynb`: The main Jupyter Notebook containing data preparation, tokenizer training, model initialization, and the training loop.

## Usage
You can open the `.ipynb` file in Jupyter Notebook, Google Colab, or Kaggle to run the training pipeline. 

Model weights and checkpoints are hosted on Hugging Face: [logicwahid/Kotha-S1](https://huggingface.co/logicwahid/Kotha-S1)

## License
This project is licensed under the Apache 2.0 License. See the LICENSE file for details.
