# Summarizer + Translator

This folder contains a Colab notebook that demonstrates **text summarization and translation** using Hugging Face Transformers.

## Project Details

- **Summarization:** Uses `facebook/bart-large-cnn` to summarize long English text into a concise version.  
- **Translation:** Uses `Helsinki-NLP/opus-mt-en-hi` to translate the English summary into Hindi.

## Files

- `summarizer_translator.ipynb` — Main notebook containing the code.

## Requirements

Install the following Python packages to run the notebook locally:

```bash
pip install transformers torch
