# 34ML

# AI Chatbot 

This project is an AI-powered chatbot built to explore and understand real website content, specifically built with the 34ML site in mind. It scrapes a live website, extracts meaningful information, and lets users ask questions about the content.

It uses:
- **Selenium** for dynamic scraping
- **BeautifulSoup** for HTML parsing
- **Sentence-Transformers** for chunk embedding
- **FAISS** for fast vector-based retrieval
- **Together AI (Mistral)** the LLM model used

---

## Features

- Scrapes both visible text and meta tags from dynamic websites
- Chunks and embeds content for efficient search
- Chat interface powered by a large language model
- Can answer questions and generate social media posts 

---

## Files

- `34ML_Task.ipynb` – the full notebook with scraping, chunking, vector indexing, and chatbot logic
- `scraper.py` – helper functions for scraping, indexing, and chatting
- `app.py` – optional frontend for interactive chatting (Streamlit)

---

## Basic Setup Instructions

1. **Download the notebook file** `34ML_Task.ipynb`
2. **Upload it to [Google Colab](https://colab.research.google.com/)**
3. Once open, click **`Runtime > Run all`** to execute all the cells sequentially
4. The last cell will generate a **public link** to the Streamlit app

Click the link, and your chatbot will be running. 






