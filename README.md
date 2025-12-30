🧠 AI-Powered Mental Health Chatbot

An AI-driven mental health support chatbot designed to provide empathetic, anonymous, and accessible emotional assistance using Generative AI and Natural Language Processing (NLP). The chatbot acts as a first-line support system, offering a safe, stigma-free space for users to express their feelings anytime, anywhere.

✨ Key Features

💬 Empathetic Conversations – Generates human-like, supportive responses using a fine-tuned transformer model

🕒 24/7 Availability – Always accessible, unlike traditional therapy services

🔐 Privacy-First Design – No user data storage; secure API-based communication

🧠 Context-Aware Responses – Maintains session-based chat history for meaningful conversations

🌿 Self-Care & Mindfulness Support – Provides stress management tips, grounding exercises, and motivational guidance

🎨 Calming UI/UX – Built with Streamlit featuring avatars, animations, and soothing themes

🛠️ Tech Stack

Programming Language

Python

AI & NLP

Transformer-based LLM: google/gemma-2-2b-it

Hugging Face Transformers & Inference API

Sentiment Analysis & Tokenization

Frontend

Streamlit

Security & Deployment

Environment variables (.env) for API key protection

HTTPS-based API calls

Deployed on Streamlit Cloud

🏗️ System Architecture

User Interface (Streamlit) – Accepts user input and displays responses

AI Processing Layer – Processes input using a fine-tuned LLM via Hugging Face API

Response Handling – Formats empathetic replies and maintains session memory

Security Layer – Ensures confidentiality with no data persistence

📊 Dataset & Model Training

Dataset: ramachaitanya22/mental_health_and_fitness_data

Cleaned and preprocessed text data (tokenization, normalization, stopword handling)

Fine-tuned the pretrained model using supervised learning to improve emotional understanding and response relevance
