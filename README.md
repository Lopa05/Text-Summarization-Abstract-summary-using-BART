# Text Summarisation with BART (T8)

This project demonstrates **abstractive text summarisation** using Hugging Face's **BART model** (`facebook/bart-large-cnn`) on the **CNN/DailyMail dataset**.  
Implemented in Jupyter Notebook: **Text summarisation T8.ipynb**.

---

## Description
Text summarisation is the task of shortening long pieces of text into concise and coherent summaries while preserving meaning.  
This notebook:
- Loads the **CNN/DailyMail dataset** (a standard benchmark for summarisation).  
- Uses a **pre-trained BART model** to generate summaries.  
- Evaluates performance using **ROUGE metrics**.  
- Provides simple preprocessing and summarisation functions.  

---

## Requirements
- Python 3.8+
- Jupyter Notebook
- Install dependencies:
  ```bash
  pip install transformers torch datasets rouge-score nltk ipywidgets

