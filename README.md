# Question Answering on Persian Data

**Spring 2024 Natural Language Processing Course Project**

## Description

A question answering system designed for Persian text, leveraging retrieval-augmented generation (RAG) models. This project uses `all-MiniLM-L6-v2` for document retrieval and `GPT-2` for generating answers, with evaluation based on standard metrics.

## Features

- **Retriever Model**: `all-MiniLM-L6-v2`
- **Generator Model**: `GPT-2`
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-score

## Technologies

- **Languages**: Python
- **Libraries**: Transformers, Accelerate, Bitsandbytes, Hazm, Clean-Text, docx2txt

## Usage
- Data Cleaning: Preprocess Persian text data using the cleaning function.
- Retrieval: Encode and save text embeddings using the all-MiniLM-L6-v2 model.
- Question Answering: Generate answers using the GPT-2 model based on retrieved documents.

## Acknowledgments
Thanks to the creators of the Transformers, SentenceTransformers, and Hazm libraries.

## Special thanks to my teammates:
- **Melika Mohammadi Fakhar** - [LinkedIn](https://www.linkedin.com/in/melika-mohammadi-fakhar-25b126201)
- **Setare Babajani** - [LinkedIn](https://www.linkedin.com/in/setareh-babajani)
