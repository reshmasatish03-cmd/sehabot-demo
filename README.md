# SehaBot – Healthcare FAQ Chatbot (Demo)

SehaBot is a **demo project** showcasing how to build a custom chatbot using **n8n** and **vector search (RAG)**.  
It is designed to provide **safe, general health and wellness information** with a focus on **public health guidance in Oman**.  

## ✨ Features
- Retrieval-Augmented Generation (RAG) pipeline  
- Knowledge base from Markdown docs (wellness, hydration, heat safety, vaccination, etc.)  
- Context-aware chatbot workflow in **n8n**  
- Guardrails to prevent diagnosis, dosage, or unsafe medical advice  
- Always shows a **safety disclaimer** and refers to professional help when needed  

## ⚠️ Disclaimer
SehaBot provides **general health information only**.  
It is **not** a substitute for professional medical advice, diagnosis, or treatment.  
For emergencies in Oman, call **9999**.  

## 📂 Repo Structure
```
data/       → Knowledge base documents (Markdown)  
prompts/    → Prompt templates for RAG  
metadata/   → Source metadata (e.g., WHO, Oman MOH)  
README.md   → Project overview  
```
