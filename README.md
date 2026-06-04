# Building GPT From Scratch

**An interactive, slide-by-slide walkthrough of Andrej Karpathy's [nanoGPT](https://github.com/karpathy/nanoGPT) lecture code.**

Every one of the ~200 lines of Python is explained — from raw text to a working character-level language model with ~10.4M parameters.

---

## [Launch Presentation](https://brendanjameslynskey.github.io/nanoGPT_presentation/)

---

## What's Covered

| Part | Topic |
|------|-------|
| 1 | **Data & Tokenization** — loading text, building a character-level vocabulary, encoding and decoding |
| 2 | **Data Batching** — train/val splits, context windows, batch construction |
| 3 | **Self-Attention** — dot-product attention, masking, multi-head attention from scratch |
| 4 | **The Transformer Block** — layer norm, feed-forward network, residual connections |
| 5 | **The Full GPT Model** — stacking blocks, token + position embeddings, the language model head |
| 6 | **Training & Generation** — loss, the AdamW optimiser, autoregressive text generation |

The presentation closes with an architecture summary, a comparison of nanoGPT to GPT-4, and key takeaways.

## Format

Built with [Reveal.js](https://revealjs.com/). Use `→` to advance, `↓` for sub-sections, and `Esc` for the slide overview.

## Part of

This deck belongs to two series in the [LLMs](https://github.com/BrendanJamesLynskey/LLMs) collection:

- **[Karpathy: Neural Networks Zero to Hero](https://github.com/BrendanJamesLynskey/LLM_Hub_Karpathy_Zero_to_Hero)** — walkthroughs of Andrej Karpathy's from-scratch teaching codebases (micrograd, makemore, minbpe, minGPT, nanoGPT, llm.c, nanochat).
- **[Transformer Architecture](https://github.com/BrendanJamesLynskey/LLM_Hub_Transformer_Architecture)** — decoder-only transformer internals, from a visual walkthrough to RTL and from PyTorch to quantisation.

The [LLMs](https://github.com/BrendanJamesLynskey/LLMs) hub is a set of interactive resources covering transformer internals, agent architectures, CUDA programming, and more.
