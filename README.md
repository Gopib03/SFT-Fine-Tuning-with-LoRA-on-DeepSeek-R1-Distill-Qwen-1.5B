Scalable SFT Fine-Tuning with LoRA on DeepSeek-R1-Distill-Qwen-1.5B
Overview

This project demonstrates large-scale supervised fine-tuning (SFT) using LoRA/QLoRA on a distilled reasoning model, optimized for performance and cost efficiency.

Training Setup

Model: DeepSeek-R1-Distill-Qwen-1.5B

Dataset: 1M instruction samples

Trainer: TRL SFTTrainer

Fine-tuning method: LoRA / QLoRA

Performance

Throughput: 200K+ examples/sec

Training loss: 1.46 → 1.37

Validation loss: 1.31

Optimization Techniques

Tuned:

LoRA rank

LoRA alpha

Learning rate

Achieved better generalization and stable convergence

Deployment

Model deployed to Hugging Face Hub

Supports 16K token long-context instruction following

Ready for downstream production applications

Tech Stack

Python

Hugging Face Transformers

TRL

PEFT

LoRA / QLoRA

Applications

Instruction-following assistants

RAG backends

Agent reasoning models
