# qa_with_llamaindex

# Llama Q&A Assistant

This project is a Question and Answer (Q&A) assistant utilizing the capabilities of LlamaIndex and HuggingFace models. The assistant is designed to answer questions accurately based on the provided instructions and context. It leverages the `meta-llama/Llama-2-7b-chat-hf` model for language generation and `sentence-transformers/all-mpnet-base-v2` for embedding documents.

## Features

- **Accurate Q&A**: Provides accurate answers to user queries.
- **HuggingFace Integration**: Uses HuggingFace models for both language generation and embedding.
- **Large Context Window**: Supports a context window of up to 4096 tokens.
- **Optimized Performance**: Utilizes 8-bit model loading for efficient performance.

## Installation

To set up the project, follow these steps:

1. Clone the repository
2. Install the required Python packages
3. Log in to HuggingFace CLI to access the models

## Usage
1. Prepare your documents: Place the documents you want to load and query in the /documents directory.
2. Load the documents and initialize the models.
3. Query the assistant.

##Example
After setting up and running the assistant, you can query it with a question such as:
```python
question = "Explain the meaning of cross-attention"
response = query_engine.query(question)
print(response)
```

# Thank You!
