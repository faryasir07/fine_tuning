# 🧠 Qwen2-VL Fine-tuning on LaTeX Image-Text Dataset

This project demonstrates how to fine-tune Alibaba’s [Qwen2-VL](https://huggingface.co/Qwen/Qwen2-VL) vision-language model to understand and generate LaTeX code from complex images.

> 📍 Notebook hosted on: [Kaggle Notebook Link](https://www.kaggle.com/code/yasirfarooqui07/qwen2-vl-finetune-latex)

## 📚 Objective

- Fine-tune `Qwen2-VL` to generate LaTeX code from visual prompts.
- Leverage visual tokenization with `unsloth`, LoRA, and Hugging Face's trainer.

## 🚀 Features

- Uses `Unsloth` for optimized memory-efficient fine-tuning
- LoRA-based parameter-efficient training
- Mixed image-text support
- Notebook-friendly, Kaggle GPU-ready setup

## 🛠 Setup

You don’t need to install anything on Kaggle — just enable GPU in settings.

If running locally:
```bash
pip install unsloth peft trl bitsandbytes transformers accelerate datasets
