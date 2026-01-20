# Decoder-Only Transformer for Arithmetic Reasoning

This repository implements a **decoder-only Transformer model** trained to solve **arithmetic problems** using **PyTorch**.  
The project focuses on understanding how far a **GPT-style architecture** can learn numerical reasoning from sequence data.

---

## 🎯 Objective

- Build a **custom decoder-only model**
- Train it on **arithmetic tasks** (addition, subtraction, etc.)
- Predict the **final numeric answer** from a natural-language or symbolic input
- Understand the **limitations of Transformers** on algorithmic reasoning

---

## 🧠 Model Overview

- **Architecture:** Decoder-only Transformer  
- **Attention:** Masked self-attention (causal)  
- **Loss:** Cross-entropy  
- **Framework:** PyTorch  
- **Training Style:** Autoregressive  

The model learns to generate the answer **token-by-token**, similar to GPT-style language models.

---

## 🙏 Acknowledgement

This project is **largely based on the work and tutorials by Andrej Karpathy**, particularly his *GPT from scratch* and *nanoGPT* implementations.

Most of the core Transformer and training logic follows his original structure, with **slight modifications and extensions** made to:

- Adapt the model for **arithmetic-specific tasks**
- Experiment with **custom datasets and tokenization**
- Add evaluation logic focused on **numerical reasoning**

All credit for the foundational architecture and implementation ideas goes to **Andrej Karpathy**.
