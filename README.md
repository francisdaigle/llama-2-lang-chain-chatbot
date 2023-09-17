# Llama 2 Lang Chain Chatbot

This repository contains a chatbot demonstration built using the `Llama 2` model and the `LangChain` framework, implemented within a Jupyter Notebook. **This demonstration shows how to set up a Llama 2 chatbot in about 100 lines of code.**

## Description

This chatbot utilizes the `meta-llama/Llama-2-7b-chat-hf` model for conversational purposes. By accessing and running cells within `chatbot_1_0_0.ipynb` on Google Colab, users can initialize and interact with the chatbot in real-time. This simple demonstration is designed to provide an effective and concise example of leveraging the power of the Llama 2 model for chatbot applications.

## Setup on Google Colab

### Accessing the Notebook

1. Clone this repository:
    
        git clone https://github.com/francisdaigle/llama-2-lang-chain-chatbot.git

2. Navigate to [Google Colab](https://colab.research.google.com/).

3. Click on `File > Upload notebook`.

4. Choose the `chatbot_1_0_0.ipynb` file from the cloned repository on your local machine.

### Hugging Face Access Token

Before you can fully utilize the chatbot, you'll need a Hugging Face access token. This token allows you to access certain models from the Hugging Face model hub. Here's how to obtain it:

1. Create an account or sign in to [Hugging Face](https://huggingface.co/join).
2. Navigate to your profile settings.
3. Under the **Access Tokens** section, you'll find your token. If you don't see a token, you can generate a new one.
4. Copy the token and replace the placeholder `HF_ACCESS_TOKEN` in the `.env_template`.
5. Rename `.env_template` to `.env`.

**Note**: Always keep your access tokens secret. Do not share your notebook with the token visible to others.

### Running the Chatbot on Colab

1. Before running the cells, ensure the Colab runtime is set to use a GPU (click on `Runtime > Change runtime type` and select a GPU).

2. Run the cells in sequence to install necessary dependencies, initialize, and interact with the chatbot (click on `Runtime > Run all`).

## Features

- Uses the `Llama 2` model for advanced conversational capabilities.
- Incorporates 4-bit quantization to speed up inference and reduce GPU RAM requirements.
- Step-by-step implementation and interaction guide within the Google Colab Notebook.
- Concise demonstration with less than 100 lines of code.