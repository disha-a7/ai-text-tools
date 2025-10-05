# Study Helper App

This folder contains a Colab notebook that demonstrates a **study helper tool** using Hugging Face Transformers and Gradio.

## Project Details

- **Summarization:** Summarizes long notes or text into concise key points using `facebook/bart-large-cnn`.  
- **Question Generation:** Generates study questions from the notes using `iarfmoose/t5-base-question-generator`.  
- **Gradio App:** Provides an interactive interface where users can input their notes and get:
  - A summarized version of the notes
  - Generated study questions

## Files

- `study_helper_app.ipynb` — Main notebook containing the code.  
- `requirements.txt` — Python packages needed to run the notebook (optional but recommended).  

## Requirements

Install the following Python packages to run the notebook locally:

```bash
pip install transformers torch gradio
