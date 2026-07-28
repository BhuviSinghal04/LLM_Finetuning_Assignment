# LLM Fine-Tuning Assignment

This repository contains the notebook and dataset splits used for fine-tuning a Large Language Model (LLM) as part of an academic assignment.

## Repository Structure

```
LLM_Finetuning_Assignment/
│
├── ASSIGNMENT_final.ipynb
└── dataset_splits/
    ├── train_split.jsonl
    ├── validation_split.jsonl
    └── test_split.jsonl
```

## Contents

### ASSIGNMENT_final.ipynb

The main Jupyter Notebook containing the complete workflow:

- Dataset loading
- Data preprocessing
- Dataset splitting
- Baseline inference
- LoRA fine-tuning
- Model evaluation
- Performance comparison

### dataset_splits/

Contains the processed dataset used during training.

| File | Description |
|------|-------------|
| `train_split.jsonl` | Training dataset |
| `validation_split.jsonl` | Validation dataset |
| `test_split.jsonl` | Test dataset |

## Technologies Used

- Python
- PyTorch
- Hugging Face Transformers
- PEFT (LoRA)
- Accelerate
- Jupyter Notebook

## Objective

The objective of this assignment is to fine-tune a pre-trained Large Language Model using parameter-efficient fine-tuning techniques and evaluate its performance on the provided dataset.

## Author

**Bhuvi Singhal**

GitHub: https://github.com/BhuviSinghal04
