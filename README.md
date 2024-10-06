# LLama3 Local Setup and Public Access via Ngrok

This repository contains a Jupyter notebook (`.ipynb`) that guides you through two key tasks:

1. **Installing Ollama Locally**: Provides a method to install Ollama on your local machine.
2. **Running LLama3 Locally and Exposing It Publicly with Ngrok**: Helps you run the LLama3 model locally and configure Ngrok to expose the model, enabling public access.

## Features

- **Simple Setup**: Step-by-step instructions for installing Ollama and running LLama3 locally.
- **Public Access**: Expose the locally running LLama3 model to the internet using Ngrok.

## Prerequisites

Ensure you have the following installed before running the notebook:

- Python 3.x
- Jupyter Notebook or JupyterLab
- An Ngrok Auth Token (available after signing up on [Ngrok's website](https://ngrok.com/))

## Installation and Setup

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/your-repository-url.git
   cd your-repository


2. **Creating .env file**:
   ```bash
   echo "NGROK_AUTH_TOKEN=<your_ngrok_auth_token>" > .env

3. **Open the Jupyter Notebook**:
   ```bash
   jupyter notebook

4.**Run the Notebook**:
   The notebook is divided into two main sections:

   - **Installing Ollama**: Follow the instructions to install Ollama. 
   - **Running LLama3 with Ngrok**: Set up the LLama3 model and use Ngrok to expose it to the public.

5. **Access the LLama3 Model Publicly**:
   After running the notebook, you can access your model publicly. To find the public-facing URL:
   - Visit your Ngrok dashboard.
   - Navigate to the Ngrok Agents section.
   - Find the Public URL of your running LLama3 model. This URL allows external access to your locally hosted model.
   
## USAGE

- Once the notebook is run, the LLama3 model will be running on your local machine.
- Ngrok will provide a public URL, allowing remote access to your LLama3 instance.

