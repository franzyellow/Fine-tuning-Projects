---
library_name: peft
license: llama3.1
base_model: meta-llama/Meta-Llama-3.1-8B
tags:
- base_model:adapter:meta-llama/Meta-Llama-3.1-8B
- lora
- sft
- transformers
- trl
pipeline_tag: text-generation
model-index:
- name: llama3.1_8B_pricer-2025-10-22_00.05.08
  results: []
---

<!-- This model card has been generated automatically according to the information the Trainer had access to. You
should probably proofread and complete it, then remove this comment. -->

[<img src="https://raw.githubusercontent.com/wandb/assets/main/wandb-github-badge-28.svg" alt="Visualize in Weights & Biases" width="200" height="32"/>](https://wandb.ai/franzhuang027-university-of-amsterdam/llama3.1_8B_pricer/runs/73rqbpcm)
# llama3.1_8B_pricer-2025-10-22_00.05.08

This model is a fine-tuned version of [meta-llama/Meta-Llama-3.1-8B](https://huggingface.co/meta-llama/Meta-Llama-3.1-8B) on an unknown dataset.

## Model description

More information needed

## Intended uses & limitations

More information needed

## Training and evaluation data

More information needed

## Training procedure

### Training hyperparameters

The following hyperparameters were used during training:
- learning_rate: 0.0001
- train_batch_size: 12
- eval_batch_size: 1
- seed: 42
- optimizer: Use OptimizerNames.PAGED_ADAMW with betas=(0.9,0.999) and epsilon=1e-08 and optimizer_args=No additional optimizer arguments
- lr_scheduler_type: cosine
- lr_scheduler_warmup_ratio: 0.03
- num_epochs: 1

### Framework versions

- PEFT 0.17.1
- Transformers 4.57.1
- Pytorch 2.9.0+cu128
- Datasets 3.6.0
- Tokenizers 0.22.1