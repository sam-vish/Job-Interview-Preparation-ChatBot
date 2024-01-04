# Job Interview Preparation ChatBot

This Streamlit-based application is designed to assist users in preparing for job interviews by providing guidance and information through a chatbot interface.

## Overview

The application utilizes several libraries and functions to create a conversational retrieval chain, load relevant documents, process text, create embeddings, and employ language models for generating responses. It leverages Streamlit's user interface to allow users to interact with the chatbot by asking job interview-related questions.

## Features

- **Document Loading:** Loads documents in PDF format from the specified directory for use in generating responses.
- **Text Processing:** Splits loaded documents into smaller chunks of text to facilitate better retrieval and analysis.
- **Embeddings Generation:** Utilizes Hugging Face's sentence-transformers to generate embeddings for text chunks.
- **Vector Store Creation:** Uses FAISS to create a vector store for efficient text retrieval.
- **Language Model Usage:** Implements CTransformers to create an LLMS (Language Learning and Memory System) model for generating responses based on user queries.
- **Conversation History:** Maintains a conversation history for the chatbot, enabling a memory-based response system.

## Installation

To run the application, ensure you have Python installed. Clone this repository and install the necessary dependencies listed in the `requirements.txt` file using the following commands:

```bash
git clone <repository_URL>
cd <repository_directory>
pip install -r requirements.txt
```
## Usage

Once the dependencies are installed, execute the application by running:

```bash
streamlit run main.py
