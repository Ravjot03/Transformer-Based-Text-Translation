# Seq2Seq Transformer Model for Language Translation

This project implements a Sequence-to-Sequence (Seq2Seq) Transformer model for language translation using PyTorch and TorchText. The model is trained on the Multi30k dataset, which contains parallel English-German sentence pairs. Key components include tokenization, vocabulary creation, positional encoding, and the Transformer architecture.

## Dataset
The Multi30k dataset provides parallel English-German sentences for machine translation tasks. Due to broken URLs in TorchText’s default dataset links, modified URLs are used to fetch the training and validation data.

- Train Data: ~29K sentence pairs
- Validation Data: ~1K sentence pairs
