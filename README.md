# LightweightFineTuning
Apply Lightweight Fine-Tuning to a Foundation Model
## Lightweight Fine-Tuning with LoRA on IMDB Sentiment Analysis

This project demonstrates the use of Low-Rank Adaptation (LoRA), a Parameter-Efficient Fine-Tuning (PEFT) technique, to fine-tune a pre-trained `distilbert-base-uncased` model for binary sentiment classification on the IMDB movie reviews dataset. 

## Overview

The notebook provides a step-by-step guide to:
1. Load and preprocess the IMDB dataset.
2. Apply the LoRA technique to fine-tune the `distilbert-base-uncased` model.
3. Train and evaluate the model using the HuggingFace `Trainer` class.
4. Save and reload the fine-tuned model.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Details](#details)
  - [PEFT technique](#peft-technique)
  - [Model](#model)
  - [Evaluation approach](#evaluation-approach)
  - [Fine-tuning dataset](#fine-tuning-dataset)
- [Results](#results)
- [License](#license)

## Installation

To run this project, you need to have Python and the following packages installed:

- `transformers`
- `datasets`
- `peft`
- `torch`

You can install the required packages using pip:

```bash
pip install transformers datasets peft torch
