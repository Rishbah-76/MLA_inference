# RopeLessMLA

A PyTorch implementation of a **Rope-less Multi-Head Latent Attention (MLA)** layer.  
This module replaces the standard key-value (KV) cache with a **latent KV representation**, reducing memory usage while keeping attention computation efficient.

---

## Features
- Multi-head latent attention without rotary embeddings.
- Latent compression of keys and values for memory efficiency.
- Drop-in replacement for standard attention layers.
- Causal masking support for autoregressive decoding.

---
