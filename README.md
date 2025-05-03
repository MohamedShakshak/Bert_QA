# BERT-QA-SQuAD2 LoRA Adapter 🚀

[![Hugging Face Model]](https://huggingface.co/MohamedShakhsak/bert-qa-squad2_V2)

A **parameter-efficient** (LoRA) fine-tuned BERT model for **question answering** on SQuAD 2.0, achieving **45.95 F1** with only **0.8% trainable parameters** of the base model.

## Key Features ✨

- 🏗️ **LoRA-optimized** - 3MB adapter for `bert-base-uncased`
- ⚡ **Efficient training** - 3hrs on single T4 GPU
- 📊 **Competitive performance** - 37.16 EM / 45.95 F1
- � **Easy integration** - Works with Hugging Face `pipeline`

## Installation 📦

```bash
pip install torch transformers peft accelerate evaluate
