
# Data & AI Portfolio: Malaysian Retail & Labor Insights

This repository contains a collection of projects designed to solve real-world Malaysian business challenges using  **Artificial Intelligence** ,  **Relational Databases** , and  **Business Intelligence** .

---

# Project 1: Malaysia Labor Law AI (RAG System)

An AI-powered Retrieval-Augmented Generation (RAG) application designed to help HR professionals and employees navigate the **Employment Act 1955** (including 2022 amendments).

### Interface Preview

<p align="center">
  <img src="malaysian%20Legal%20AI/picture/Streamlit_example.png" width="800">
</p>

## Key Features

* **Document Ingestion:** Automated processing of legal PDF documents into searchable chunks.
* **Vector Search:** Uses `ChromaDB` and `HuggingFace` embeddings for semantic retrieval.
* **AI Reasoning:** Powered by `Llama-3.3-70b` via Groq for high-speed, legally-grounded responses.
* **Interactive UI:** A clean `Streamlit` interface for natural language querying.

## Tech Stack

* **Programming Language:** Python
* **LLM:** Groq (`Llama-3.3-70b-versatile`)
* **Framework:** LangChain
* **Vector Database:** ChromaDB
* **Embeddings:** HuggingFace (`all-MiniLM-L6-v2`)
* **Frontend / App Interface:** Streamlit
* **Data Source:** Malaysian Employment Act 1955 (PDF)

---

# Project 2: Malaysia E-commerce Sales Analytics

An end-to-end BI solution analyzing **10,000+ sales records** from Shopee, Lazada, and TikTok Shop to decode Malaysian consumer behavior in 2024.

### Dashboard Preview

<p align="center">
  <img src="Malaysia%20E-commerce%20Sales%20Analytics/E-commerce%20Dashboard.png" width="800" alt="E-commerce Dashboard Preview">
</p>

## Key Features

* **SQL Data Pipeline:** Developed a cleaning pipeline to handle nulls, remove duplicates, and validate 10k+ rows of raw retail data.
* **Exploratory Data Analysis (EDA):** Uncovered that **May and July** were peak months (Totaling ~RM 53M) and identified the **Xiaomi Redmi Note 12** as the primary revenue driver (RM 33.7M).
* **Multi-Platform Strategy:** Proved that sales are evenly distributed across platforms, justifying a multi-channel marketing spend.
* **Power BI Dashboard:** Visualized **RM 302M in Total Profit** with interactive filters for platform share and monthly trends.

## Tech Stack

* **Database / Query Language:** SQL
* **Data Visualization:** Power BI
* **Data Processing:** SQL Aggregations & Data Cleaning
* **Dataset:** Kaggle E-commerce Sales Dataset
* **Platforms Analyzed:** Shopee, Lazada, TikTok Shop
