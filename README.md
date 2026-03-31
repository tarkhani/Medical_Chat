# Healthcare Chatbot Fine-Tuning (LoRA + Phi-3.5)

This project fine-tunes the **microsoft/Phi-3.5-mini-instruct** language model using **LoRA (Low-Rank Adaptation)** on a healthcare conversation dataset. The goal is to build a lightweight medical chatbot capable of generating helpful responses to user queries.

## Description

The model is trained on the **ChatDoctor Healthcare dataset**, which contains question-answer pairs related to medical topics. Using parameter-efficient fine-tuning (PEFT) with LoRA, the project adapts the base model without updating all parameters, making training faster and more memory-efficient.

## Features

- Fine-tunes **Phi-3.5-mini-instruct** model
- Uses **LoRA (PEFT)** for efficient training
- Processes real-world healthcare Q&A data
- Tokenization and preprocessing pipeline
- Training with Hugging Face Trainer API
- Saves fine-tuned model and tokenizer

## Libraries

- transformers
- datasets
- peft
- accelerate
- torch

## Dataset

- ChatDoctor Healthcare dataset (lavita/ChatDoctor-HealthCareMagic-100k)

