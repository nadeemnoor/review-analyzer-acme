# Acme Product Review Analyzer

An AI-powered dashboard that analyzes customer product reviews to extract
sentiment, key topics, and concise summaries.

## Features
- Upload CSV files with customer reviews
- Sentiment classification (Positive / Neutral / Negative)
- Topic detection (delivery, quality, pricing, etc.)
- One-line summaries
- Interactive dashboard & CSV export

## Tech Stack
- LLM: Mistral via Ollama
- Backend: FastAPI
- Frontend: Streamlit
- Visualization: Streamlit charts

## How to Run
1. Pull model:
   ollama pull mistral
2. Start backend:
   uvicorn backend.main:app --reload
3. Start frontend:
   streamlit run frontend/app.py
