# Medical NLP Pipeline (Google Colab)

This project is an **AI-powered Medical NLP Pipeline** that processes doctor–patient transcripts and converts them into structured clinical insights.  
It performs **medical entity extraction, summarization, sentiment & intent analysis, and SOAP note generation**.

---

## Features

- **Named Entity Recognition (NER)** — Extracts Symptoms, Diagnosis, Treatment, and Prognosis using **scispaCy + regex fallback**  
- **Summarization** — Generates concise medical summaries using **Hugging Face Transformers**  
- **Keyword Extraction** — Uses **KeyBERT** with domain-specific filtering for relevant terms  
- **Sentiment & Intent Analysis** — BERT-based emotion detection with **rule-based intent classification**  
- **SOAP Note Generation** — Converts conversations into **structured clinical notes** (Subjective, Objective, Assessment, Plan)  
- **Structured JSON Output** — All data is exported in JSON format for easy integration into dashboards or EHR systems  

---

## ⚙️ Setup Instructions (Colab)

1. Open [Google Colab](https://colab.research.google.com/).  
2. Upload the notebook (`physician_Notetaker_emitrr.ipynb`).  
3. Run the commands in order

---

## Technologies Used:

- Python
- spaCy / scispaCy
- Hugging Face Transformers
- PyTorch
- KeyBERT
