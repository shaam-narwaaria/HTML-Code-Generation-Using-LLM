# HTML Code Generation using Falcon-7B LLM Model

This repository contains code for generating HTML code using Falcon-7B, a large language model fine-tuned with the PEFT (Parameter Efficient Fine-Tuning) technique. The aim is to generate HTML code based on user prompts or instructions.

## Overview

In this project, we utilize state-of-the-art language models like Falcon-7B for generating HTML code based on user instructions. The project focuses on fine-tuning Falcon-7B using the PEFT technique to make the model efficient regarding memory usage and runtime while preserving performance.

## Features

- Utilizes Falcon-7B, a large language model, for text generation.
- Fine-tuning with the PEFT technique for efficient memory usage and runtime.
- Support for generating HTML code based on user instructions or prompts.
- Evaluation metrics such as BLEU score and custom evaluation functions are used to assess generated HTML code quality.

## Dataset
- [alpaca-instructions-dataset](https://huggingface.co/datasets/ttbui/html_alpaca)


## Prerequisites

Before running the code, ensure you have the following dependencies installed:

- Python
- PyTorch
- Transformers library from Hugging Face
- Other required Python packages (listed in requirements.txt)

## How to run on Google Colab

### Step 1
- Upload file `html-generation.ipynb` on google colab online interpreter for python.

### Step 2
- Run the cell one by one
- Hugging Face: Login using the token generated from your Hugging Face profile.
- Wandb: Paste the API key from your Wandb profile and hit enter.

### Step 3
- In the Inference Model cell paste the testcase from the input folder in the prompt section

## Evaluation Metrics

- BLEU Score: Measures the similarity between generated and expected HTML code.
- Custom Evaluation Functions: Assess relevant tags accuracy, structure accuracy, styling, and scripting elements, semantic accuracy, and overall score.


## Authors

- [Shambhoolal Narwaria](https://github.com/mr-narwaria)
- [Alhan Charan Beshra](https://github.com/ezio2605)
- [Abhishek Raj](https://github.com/Abhi9708bittu)

<br>

  Enjoy the Model!

