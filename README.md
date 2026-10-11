# German Tutor LLM

A small LLM fine-tuning project using Hugging Face and LoRA/PEFT.

## Goal

Adapt a pretrained instruction-tuned language model to behave as an
A2-level German vocabulary tutor using my curated German vocabulary.

The tutor should be able to:
- quiz vocabulary
- generate A2-level example sentences
- create EN → DE exercises
- correct simple German sentences
- explain mistakes concisely
- use vocabulary from the target word list

## Experiment

Compare:

1. Base pretrained model
2. LoRA fine-tuned model

on the same held-out German tutoring prompts.

## Planned stack

- Hugging Face Transformers
- Hugging Face Datasets
- PEFT / LoRA
- TRL / SFTTrainer
- PyTorch

## Current status

- [x] Transformer foundations
- [ ] Hugging Face inference
- [ ] Baseline model evaluation
- [ ] Dataset preparation
- [ ] LoRA fine-tuning
- [ ] Evaluation
- [ ] Final README / results