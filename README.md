Smart FAQ Chatbot (AI Syllabus-Based)

This project is a strict AI-powered FAQ chatbot built using Python, Ollama, and Streamlit.
It answers only questions related to a predefined Artificial Intelligence syllabus.

📌 Features
🧠 Uses LLM (TinyLlama via Ollama)
📚 Answers strictly based on syllabus
🗂️ Maintains chat memory
⚡ Input validation for safe queries
🌐 Simple Streamlit web interface
🔒 Enforces strict response rules
📖 Syllabus Covered
Introduction to AI
Machine Learning Basics
Neural Networks
Natural Language Processing
Computer Vision
⚙️ Requirements
Python 3.8+
Ollama installed
Streamlit

Install dependencies:

pip install streamlit ollama
🤖 Setup Ollama
Install Ollama from: https://ollama.com
Pull and run the model:
ollama run tinyllama
▶️ Run the Project
Option 1: Terminal Chatbot
python chatbot.py
Option 2: Streamlit Web App
streamlit run app.py
💡 How It Works
The chatbot is guided by a system prompt
It:
Only answers syllabus-related questions
Responds in bullet points
Uses simple English
Limits responses to max 5 points
Invalid or unrelated questions are rejected
🚫 Restrictions

The chatbot will:

❌ Not answer outside syllabus
❌ Not give explanations or examples
❌ Not exceed 5 bullet points
❌ Not respond to unsafe inputs
🧪 Example Usage

Input:

What are modules in AI course?

Output:

- Introduction to AI
- Machine Learning Basics
- Neural Networks
- Natural Language Processing
- Computer Vision
📁 Project Structure
├── chatbot.py      # CLI chatbot
├── app.py          # Streamlit app
├── README.md
⚠️ Troubleshooting
Make sure Ollama is running:
ollama run tinyllama
If Streamlit fails:
pip install --upgrade streamlit
🚀 Future Improvements
Add multiple courses
Improve UI design
Add authentication
Deploy online
👤 Author

Mahissa Salehnezhad
