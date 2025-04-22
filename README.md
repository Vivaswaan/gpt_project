
# GPT-Inspired Transformer Language Model (Final Year Major Project)

This project implements a GPT-style **decoder-only transformer language model** from scratch using PyTorch. It explores the impact of different tokenization strategies (Character-level, Byte Pair Encoding, and WordPiece) on model training and generation quality.

## 🚀 Key Features
- Manual implementation of GPT-like transformer architecture
- Multi-head masked self-attention with causal masking
- Feedforward layers, LayerNorm, residual connections
- Autoregressive text generation with sampling
- Custom training loop with loss and perplexity tracking
- Comparison of 3 tokenizers:
  - Character-level (custom)
  - Byte-Pair Encoding (via HuggingFace)
  - WordPiece (via HuggingFace)

## 🧠 Concepts Covered
- Transformers and self-attention
- Token embeddings + positional embeddings
- Cross-entropy loss and perplexity
- Optimizer: AdamW with weight decay
- Tokenization and vocabulary optimization

## 📊 Experiments
- Trained on *Frankenstein* by Mary Shelley
- Measured training and validation loss, perplexity
- Generated text samples with each tokenizer
- Plotted training curves to visualize convergence

## ⚙️ Tech Stack
- Python 3
- PyTorch
- Hugging Face `tokenizers`
- Google Colab (with CUDA GPU)
- Matplotlib

## 📁 Files
- `gpts_proj_.ipynb` — main project notebook
- `frankenstein.txt` — training corpus
- `gpt_project_report.pdf` — final project report

## 📚 Literature
- Vaswani et al., *Attention Is All You Need*
- Radford et al., *GPT-1*
- Devlin et al., *BERT*
- Sennrich et al., *BPE for NMT*
- Liu et al., *Training Transformers*

## 🔍 Author
- **Name**: Vivaswaan
- **Degree**: B.Tech CSE Final Year
- **University**: Maulana Azad National Institute of Technology, Bhopal
