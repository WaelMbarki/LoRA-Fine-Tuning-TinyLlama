# Fine-Tuning TinyLlama with LoRA on GSM8K

This repository contains code to fine-tune the TinyLlama-1.1B language model using Low-Rank Adaptation (LoRA) on the GSM8K dataset of grade-school math word problems.

---

## Project Overview

- **Model:** TinyLlama-1.1B (HuggingFace)
- **Dataset:** GSM8K (grade-school math problems)
- **Technique:** LoRA (Low-Rank Adaptation) for parameter-efficient fine-tuning
- **Quantization:** 4-bit quantization using BitsAndBytes for memory efficiency
- **Evaluation:** Model performance measured by perplexity and ability to generate step-by-step math solutions

---

## Usage

### Training

Train the model by running the notebook:

- [`fine_tuning_TinyLlama.ipynb`](fine_tuning_TinyLlama.ipynb)

Download and run this notebook to fine-tune TinyLlama on the GSM8K dataset.

### Evaluation

Evaluate the fine-tuned model by running the notebook:

- [`evaluate_TinyLlama.ipynb`](evaluate_TinyLlama.ipynb)

This notebook computes perplexity and tests the model's ability to generate math problem solutions.
