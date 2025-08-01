# 🦠 Nova Scotia Pandemic/Epidemic Real-Time Chatbot

## 📌 Project Overview

This project is an educational chatbot designed to assist residents of Nova Scotia in accessing real-time, local pandemic and epidemic information. Using a retrieval-augmented generation (RAG) framework powered by the Ollama + AnythingLLM stack, the chatbot delivers quick, accurate answers to questions about:

- Local COVID-19 case counts
- Travel restrictions and requirements
- Public health guidelines

⚠ **Disclaimer:** This chatbot does **not** provide medical diagnosis or treatment. It is for informational and research purposes only. For health concerns, contact a licensed healthcare provider.

## 🧱 Project Structure

```
/cold-flu-chatbot
├─ knowledge_base/
│  ├─ knowledge_document_1.pdf
│  ├─ knowledge_document_2.md
│  └─ knowledge_document_3.txt
├─ prompt/
│  └─ system_prompt.txt
├─ documentation/
│  ├─ scenario_pack.md
│  └─ use_case_description.md
├─ demo/
│  ├─ demo_video.mp4
│  └─ chat_transcript.txt
└─ README.md
```

## 🚀 Local Deployment & Testing Instructions

### Prerequisites
- [AnythingLLM](https://github.com/Mintplex-Labs/anything-llm)
- [Ollama](https://ollama.com)

### Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/cold-flu-chatbot.git
   cd cold-flu-chatbot
   ```

2. **Install AnythingLLM**  
   Follow the instructions from the [AnythingLLM GitHub repository](https://github.com/Mintplex-Labs/anything-llm) to install and launch the UI.

3. **Install Ollama**  
   Follow setup from [Ollama](https://ollama.com) to get your local LLM environment running.

4. **Upload Knowledge Base**  
   Use the AnythingLLM UI to upload all files under `/knowledge_base`.

5. **Configure System Prompt**  
   Upload the file from `/prompt/system_prompt.txt` to define chatbot behavior.

6. **Test Scenarios**  
   Ask questions such as:
   - "How many new COVID-19 cases were reported in Nova Scotia today?"
   - "How many new COVID-19 cases were reported in Nova Scotia 3 months ago?"

   Validate that responses are accurate and include the medical disclaimer.

## 👥 Authors

- Project Team: Prithika Suwal  
- Date: July 31, 2025
