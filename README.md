# Building LLMs From Scratch 🧠📚

This project demonstrates the foundational concepts behind building a Transformer-based Language Model from scratch, inspired by GPT-like architectures. It includes end-to-end components such as tokenization, positional encoding, multi-head self-attention, feedforward layers, and training loop on a small text corpus.

## 🚀 Features

- Byte Pair Encoding (BPE) tokenizer using `tiktoken`
- Custom Transformer Encoder implementation
- Multi-Head Attention, Layer Normalization, Residual Connections
- Positional Encoding
- Trained on a Harry Potter subset (~12M parameters)
- Next-token prediction objective
- PyTorch-based model architecture

## 🛠️ Project Structure
├── sample_corpus/ # Contains sample text (Harry Potter subset)
├── README.md
└── requirements.txt

bash
Copy
Edit

## 🔧 Setup

Clone the repo and install dependencies:

```bash
git clone https://github.com/yourusername/llm-from-scratch.git
cd llm-from-scratch
pip install -r requirements.txt
