# 👶 Babywise AI Chatbot

An AI-powered assistant designed to support new parents with evidence-based, structured, and relatable guidance on infant care for babies aged 0–1 year.

Whether you're navigating growth spurts, decoding sleep patterns, or seeking expert-backed feeding tips, **Babywise AI Chatbot** offers insights drawn from trusted medical sources, parenting communities, and foundational textbooks.

---

## 💡 Features

- 🤖 Chatbot trained on topics related to infant care (0–1 year)
- 📚 Multi-source knowledge base (Books, Mumsnet, Mayo Clinic, AAP, etc.)
- 🧠 Covers milestones, sleep, feeding, vaccines, emotional development & more
- 🗣️ Mixed tone: medical accuracy + human-centered insights
- 🧩 Modular architecture with future extensibility (books, docs, web)

---

## 🧠 Knowledge Categories

1. Developmental Leaps & Brain Growth  
2. Growth Spurts  
3. Tummy Time  
4. Infant Sleep & Sleep Training  
5. Infant Feeding  
6. Vaccines / Medications  
7. Common Illnesses  
8. Emotional & Behavioural Development  
9. Environmental Factors & Development  
10. Parent Self-care & Relationships  
11. Extras – Humor, Anecdotes, Conflicting Advice (Doctors vs Parents)

---

## 📂 Project Structure

babywise-ai-chatbot/
├── data/ # Curated knowledge base (PDFs, articles, scraped pages)
├── docs/ # Structured JSON/Markdown per category
├── src/
│ ├── agents/ # AI agent logic
│ ├── chains/ # Prompt chains / RAG pipelines
│ ├── retriever/ # Vector DB, embeddings
│ └── app.py # Main chatbot app (FastAPI / Streamlit)
├── notebooks/ # Research or data extraction notebooks
├── requirements.txt # Dependencies
└── README.md # You're here
