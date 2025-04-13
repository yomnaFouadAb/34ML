# 34ML

# 🧠 34ML Web Scraping + AI Chatbot (RAG-based)

This project is a smart, context-aware chatbot that scrapes the content of a website (e.g. [34ml.com](https://34ml.com)) and lets users ask natural-language questions about the site.

It uses:
- ✅ **Selenium** for dynamic scraping
- ✅ **BeautifulSoup** for HTML parsing
- ✅ **Sentence-Transformers** for chunk embedding
- ✅ **FAISS** for fast vector-based retrieval
- ✅ **Together AI (Mistral)** for answering user queries

---

## 💡 Features

- 🔍 Scrapes both visible text and meta tags from dynamic websites
- 🔁 Chunks and embeds content for efficient search
- 🧠 Uses a **retrieval-augmented generation (RAG)** approach
- 💬 Chat interface powered by a large language model
- ⚡ Can answer questions like:
  - “What does this company offer?”
  - “Summarize their blog”
  - “Write a tweet about their services”

---

## 📁 Files

- `34ML_Task.ipynb` – the full notebook with scraping, chunking, vector indexing, and chatbot logic
- `scraper.py` – helper functions for scraping, indexing, and chatting (used in a Streamlit app)
- `app.py` – optional frontend for interactive chatting (Streamlit)
- `requirements.txt` – libraries used (optional)

---

## 🚀 Quick Start

```bash
git clone https://github.com/your-username/34ml-chatbot.git
cd 34ml-chatbot
pip install -r requirements.txt
python app.py  # or open 34ML_Task.ipynb

