# Llama Colab Playground

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1OnK6sY4tbD3mcwpx-wQzTvjWvmzNjvUa?usp=sharing)  

A beginner-friendly project that demonstrates how to use the Llama family of large language models (LLMs) in a Google Colab notebook. The goal is to help learners understand how to load and run inference with Llama models from Hugging Face and simulate a simple chatbot-like interaction.  

This project is purely educational and meant for hands-on experimentation.

---

## Prerequisites  

Before you begin, make sure you have:  

- A **Google account** (for running the notebook in Colab)  
- A **Hugging Face account** and an **access token** (required to use the Llama models)  

If you don’t have a Hugging Face account, create one at [huggingface.co](https://huggingface.co).  
To generate an access token:  
1. Log in to Hugging Face  
2. Go to **Settings > Access Tokens**  
3. Create a new token with the appropriate access permissions  

---

## Setup Instructions  

1. Open the Colab notebook using the badge above or directly from this repository.  
2. Install required libraries by running the following cell in the notebook.
3. Authenticate Hugging Face account using access token.(Enter your Hugging Face access token when prompted.)
4. Load tokenizer and Llama model.
Run the inference cells to start interacting with the model in a chatbot-like manner.

---

## Libraries Used

- transformers
- torch
- accelerate

---

## Notebook

All code and examples are inside the Colab notebook included in this repository. Open it in Colab and run the cells step by step to see how inference works.

---

## Notes

- The Llama models are large, so loading them in Colab may take time and require a GPU runtime.
- Ensure your Hugging Face token has permission to access the Llama models.