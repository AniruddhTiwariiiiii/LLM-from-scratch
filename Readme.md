# LLMs from Scratch

## GPT Tokenization & Data Pipeline from Scratch

This repository implements core components of a GPT-style language model pipeline, focusing on tokenization and dataset construction from first principles.

## Overview

The project explores how raw text is transformed into structured training data for GPT-like models:

- Custom tokenization and vocabulary construction
- GPT-style subword tokenization using `tiktoken`
- Sliding context windows with configurable `max_length` and `stride`
- Input–target token pair generation for next-token prediction
- PyTorch `Dataset` and `DataLoader` implementation for batching

## Key Concepts

- Tokenization: text → tokens → token IDs
- Context windowing and overlapping sequences
- Next-token prediction objective
- Efficient data loading with PyTorch

## Usage

1. Install dependencies:

```bash
pip install torch tiktoken
```
