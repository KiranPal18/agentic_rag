# Real-Time Financial Intelligence System

Submission for **Pathway H3 TechMeet’14** — Financial Agents that Work with Real-Time Insights.

---

## FILES

- **pathway.py** – main code file  
- **Pathway_H3_TechMeet14.pdf** – problem statement  
- **chromadb_langgraph/** – folder for vector storage (auto-created)  
- **README.md** – documentation

---

## WHAT IT DOES

- Simulates financial transaction and market data  
- Detects fraud in real time using online learning  
- Ranks investments based on live signals  
- Uses an LLM to generate insights and summaries

---

## HOW TO RUN

Install dependencies:

```bash
pip install chromadb sentence-transformers transformers accelerate scikit-learn pandas numpy
pip install langgraph langchain langchain-community
