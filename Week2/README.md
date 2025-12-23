# Week 2: Prompt Engineering and Fine-tuning

## Overview
This week explores prompt engineering techniques and methods for fine-tuning LLMs on specific tasks.

## Topics Covered
- Prompt Engineering Strategies
- Zero-shot and Few-shot Learning
- Instruction Fine-tuning
- Parameter Efficient Fine-Tuning (PEFT)
- LoRA (Low-Rank Adaptation)

## Assignments

### Assignment 2: Prompt Engineering
- **Objective**: Master prompt engineering techniques
- **Notebook**: `assignment2_prompt_engineering.ipynb`
- **Key Tasks**:
  - Design effective prompts for various tasks
  - Compare zero-shot vs few-shot learning
  - Implement chain-of-thought prompting
  - Evaluate prompt performance

### Lab 2: Fine-tuning with PEFT
- **Objective**: Fine-tune a model using parameter-efficient methods
- **Notebook**: `lab2_peft_finetuning.ipynb`
- **Key Tasks**:
  - Prepare a dataset for fine-tuning
  - Apply LoRA for efficient fine-tuning
  - Evaluate fine-tuned model performance
  - Compare with full fine-tuning

## Resources
- [Prompt Engineering Guide](https://www.promptingguide.ai/)
- [PEFT Documentation](https://huggingface.co/docs/peft)
- [LoRA Paper](https://arxiv.org/abs/2106.09685)

## Setup

Install additional packages for this week:
```bash
pip install peft transformers datasets evaluate
```

## Tips
- Start with simple prompts and iterate
- Keep track of what works and what doesn't
- Use evaluation metrics to compare approaches
- Consider computational costs when fine-tuning
