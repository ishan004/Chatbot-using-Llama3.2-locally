# Chatbot using Llama3.2 Locally (Ollama)

This project demonstrates how to create a local chatbot using the **Ollama Llama3.2:3B** model. It allows you to interact with an AI chatbot in a conversational manner directly from your terminal. The chatbot uses the `langchain_ollama` package to interface with the Llama3.2 model and handle user input.

## Features

- Local setup of the **Llama3.2:3B** model via **Ollama**.
- Real-time conversational interface.
- Maintain conversation history and context.
- Simple terminal-based interaction.

## Requirements

- **Python 3.7 or higher**.
- **Ollama** software installed and running (used to serve the Llama3.2:3B model).
- **langchain_ollama** package for interacting with Ollama.
- **langchain_core** package for creating prompts.

## Installation

### 1. Clone the Repository

Clone the repository to your local machine:

```bash
git clone https://github.com/ishan004/Chatbot-using-Llama3.2-locally.git
cd Chatbot-using-Llama3.2-locally
```


### 2. Set Up a Virtual Environment (Optional, but recommended)

Create a virtual environment:

```bash
python -m venv venv
```

### 3. Install Required Packages

Install the necessary Python dependencies:

```bash
pip install langchain_ollama langchain_core
```

### 4. Set Up Ollama

To run the chatbot locally, you need the **Ollama** software with the **Llama3.2:3B** model. You can follow the official [Ollama installation guide](https://ollama.com) to install the software and model.

Ensure that the **Ollama** model is running and accessible before starting the chatbot.

### 5. Run the Chatbot

Once everything is set up, run the chatbot using the following command:

```bash
python chatbot.py
```




