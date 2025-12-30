# 🧠 AI-Powered Mental Health Chatbot
### Generative AI | NLP | Privacy-First Design

An AI-driven mental health chatbot built using Generative AI and Natural Language Processing (NLP) to provide empathetic, anonymous, and 24/7 emotional support. The chatbot acts as a first-line support system with a strong focus on accessibility, privacy, and user experience.

---

## ✨ Features

- Empathetic, context-aware conversations using a transformer-based language model  
- 24/7 availability for mental health support  
- Privacy-first design with no user data storage  
- Session-based conversational memory  
- Self-care and mindfulness recommendations  
- Clean, calming user interface built with Streamlit  

---

## 🛠 Tech Stack

- **Language:** Python  
- **AI / NLP:** Hugging Face Transformers, `google/gemma-2-2b-it`  
- **Frontend:** Streamlit  
- **APIs:** Hugging Face Inference API  
- **Security:** Environment variables (`.env`), HTTPS  

---

## 🏗 How It Works

1. User enters text through the Streamlit interface  
2. Input is processed using NLP and sentiment understanding  
3. The fine-tuned LLM generates empathetic responses  
4. Session history maintains conversational context  
5. Conversations are not stored, ensuring confidentiality  

---

## 🚀 Run Locally

```bash
git clone https://github.com/your-username/mental-health-chatbot.git
cd mental-health-chatbot
pip install -r requirements.txt
pip install -r requirements.txt

Run the application:
streamlit run ui.py
