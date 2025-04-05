# 🚀 HTML Code Generation using Falcon-7B LLM Model

This repository contains the implementation for generating HTML code using **Falcon-7B**, a large language model fine-tuned using the **PEFT (Parameter Efficient Fine-Tuning)** technique. The goal is to generate accurate and semantically meaningful HTML code based on user prompts or natural language instructions.

---

## 🧠 Overview

In this project, we leverage **Falcon-7B**, a cutting-edge LLM, for HTML code generation. The model is fine-tuned using the **PEFT** technique, enabling efficient memory and computation usage without compromising performance.

---

## ✨ Features

- 🔮 **Falcon-7B** based text generation for HTML
- ⚙️ **PEFT-based fine-tuning** for lightweight training and inference
- 📝 Generates structured and semantically correct HTML from natural language prompts
- 📊 Evaluation using **BLEU Score** and **custom metrics**
- 🧪 Ready-to-use in **Google Colab** for training and inference

---

## 📂 Dataset

We use a subset of the Alpaca-style instruction dataset fine-tuned for HTML:

- 📁 [`html_alpaca` Dataset on Hugging Face](https://huggingface.co/datasets/ttbui/html_alpaca)

---

## ✅ Prerequisites

Before running the project, ensure the following dependencies are installed:

- Python ≥ 3.8
- PyTorch
- `transformers` (Hugging Face)
- `peft`
- `accelerate`
- `wandb`
- Other dependencies listed in `requirements.txt`

---

## ⚙️ How to Run on Google Colab

### 🔹 Step 1: Upload Notebook
- Upload the `html-generation.ipynb` notebook to [Google Colab](https://colab.research.google.com/)

### 🔹 Step 2: Setup Authentication
- 🔑 **Hugging Face**: Paste your Hugging Face token to login.
- 🔑 **Weights & Biases (Wandb)**: Paste your API key for tracking experiments.

### 🔹 Step 3: Run Inference
- Scroll to the **Inference Model** cell.
- Paste your desired test case from the `/input` folder into the prompt box.

---

## 📈 Evaluation Metrics

- **BLEU Score**: Evaluates n-gram similarity between generated and reference HTML.
- **Custom Metrics**:
  - ✅ Tag correctness
  - ✅ Structural accuracy
  - ✅ Styling and scripting analysis
  - ✅ Semantic correctness
  - ✅ Overall quality score

---

## 📁 Project Structure
html-falcon7b-htmlgen/
├── input/
│   └── sample_prompt.txt
├── output/
│   └── sample_output.html
├── html-generation.ipynb
├── requirements.txt
├── .gitignore
└── README.md

---

## 👨‍💻 Author

- [Shambhoolal Narwaria](https://github.com/mr-narwaria)

---

## 🌟 Acknowledgments

- Hugging Face 🤗 for Transformers and Datasets
- Wandb for experiment tracking
- The creators of the `html_alpaca` dataset

---

## 🎉 Enjoy the Model!

Feel free to fork, contribute, and share your feedback! If you like this project, give it a ⭐ on GitHub.
