# Optimizing LLMs In Practice

Hands-on notebooks: fine-tuning, distillation, alignment, quantization, embeddings.

## Notebooks

| # | Topic | Technique |
|---|-------|----------|
| 01 | BERT Classification | Full fine-tuning on IMDB |
| 02 | Embedding Fine-tuning | Contrastive learning |
| 03 | Synthetic Training Data | LLM-generated labels |
| 04 | Matryoshka Embeddings | MRL training |
| 05 | Reward Model | Pairwise preference ranking |
| 06 | RLHF Pipeline | PPO-based alignment |
| 07 | Knowledge Distillation | Teacher-student compression |
| 08 | Quantization | GGUF, AWQ, bitsandbytes |

## Quick Start

```bash
pip install -r requirements.txt
jupyter lab
```

## Hardware

| Notebook | Min VRAM | Est. Time |
|---------|---------|----------|
| 01-04 | 4GB | 20-45 min |
| 05-07 | 8GB | 60-90 min |
| 06 RLHF | 16GB | 2-4 hrs |

All notebooks fall back gracefully to CPU.
