
# Rare Disease Medical Terminology Chatbot (Gaucher Disease Focus)

This is a locally hosted AI chatbot designed to help patients and families understand complex medical terminology related to rare diseases—specifically **Gaucher disease**—using plain language. It also provides guidance on where to find support services in **Nova Scotia, Canada**.

> ⚠️ **Disclaimer:** This chatbot does not provide medical diagnoses or treatment recommendations. For medical concerns, please consult a licensed healthcare professional.

---

## 🎯 Purpose

To support patients who receive confusing genetic or diagnostic reports by:
- Explaining terms like "Gaucher disease" and "GBA mutation" in simple English
- Offering contact info and summaries of relevant support groups and clinics
- Reducing emotional stress caused by medical jargon

---

## 🛠 Technology Stack

- **Ollama** (LLM backend — e.g., Gemma3 or Mistral)
- **AnythingLLM** (Chat interface and Retrieval-Augmented Generation framework)
- **Local knowledge base** (PDFs/TXT/Markdown files)
- **System prompt engineering** for ethical scope and tone

---

## 📂 Project Structure

```
/rare-disease-chatbot/
├── knowledge_base/
│   ├── knowledge_document_1.txt   # Gaucher disease summary
│   └── knowledge_document_2.txt   # Nova Scotia support resources
├── prompt/
│   └── system_prompt.txt
├── documentation/
│   ├── scenario_pack.md
│   └── use_case_description.md
├── demo/
│   ├── demo_video.mp4
│   └── chat_transcript.txt
└── README.md
```

---

## 💬 Example Test Questions

- "What is Gaucher disease?"
- "What does GBA mutation mean?"
- "Where can I find support groups for rare disease in Nova Scotia?"

---

## 🚨 Ethical Safeguards

- Clearly communicates limitations
- Redirects crisis-related questions to emergency services
- Stores no personal or sensitive information

---

## 🚀 How to Run Locally

1. Install Ollama and pull your preferred model 
2. Clone this repo and install AnythingLLM:
   ```bash
   git clone https://github.com/Mintplex-Labs/anything-llm
   cd anything-llm
   npm install
   npm run dev
   ```
3. Create a workspace, bind to Ollama, upload files, and chat!

---

**Author**: [Feng Xue]  
**Date**: July 30th 2025  
**Institution**: Sobey School of Business, Saint Mary’s University  
