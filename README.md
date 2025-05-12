# psywell-assistant-Chatbot
AI-powered health psychology chatbot offering evidence-based mental health support using cognitive-behavioral techniques
# 🧠 Adeel Psychologist Chatbot

Adeel Psychologist Chatbot is a supportive mental wellness tool built with **OpenAI’s GPT-3.5-Turbo** and a user-friendly **Gradio interface**. It is designed to simulate a compassionate psychologist to help users with emotional support, stress management, and mental well-being.

⚠️ **Disclaimer:** This chatbot is for educational and supportive purposes only. It is **not a substitute for professional medical advice or therapy**.

---

## 💡 Features

- 🗣️ AI-powered chatbot trained with a psychologist persona
- 📘 Suggests coping strategies, relaxation tips, and emotional support
- 🌐 Simple Gradio-based web interface
- 🔒 No data stored; runs locally or via secure link

---
### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Adeel-Psychologist-Chatbot.git
cd Adeel-Psychologist-Chatbot
2. Set Up a Virtual Environment (optional but recommended)
bash
Copy
Edit
python -m venv venv
# Activate virtual environment
venv\Scripts\activate      # Windows
source venv/bin/activate   # macOS/Linux
3. Install Required Packages
bash
Copy
Edit
pip install -r requirements.txt
4. Add Your OpenAI API Key
Create a .env file in the project folder:

ini
Copy
Edit
OPENAI_API_KEY=sk-your-openai-key-here
🔐 Never share your OpenAI key publicly.

▶️ Running the App
bash
Copy
Edit
python app.py
You’ll get a local link like:
http://127.0.0.1:7860
Or a public link if share=True is enabled.
