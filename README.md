# Docuchat Gemini Chatbot

A Streamlit-based AI document assistant that answers questions from uploaded PDF, DOCX, or TXT documents using the **Google Gemini API**.

---

## 🌟 Features

- **Multi-format Document Support:** Upload PDF, DOCX, or TXT files.
- **Context-Aware Answers:** Uses Google Gemini to extract answers directly from the context of your uploaded files.
- **Interactive Chat Interface:** Clean, intuitive, conversation-style UI with session chat history.
- **Voice Output (TTS):** Integrated Text-to-Speech playback for bot responses.
- **Secure Configuration:** Environment variables via `.env` to protect API keys.

---

## 🚀 Quick Start

### 1. Clone the Repository

```bash
git clone https://github.com/prasad-tech7/Docuchat-Chatbot.git
cd Docuchat-Chatbot
```

### 2. Install Dependencies

Ensure Python 3.9+ is installed, then run:

```bash
pip install -r requirements.txt
```

### 3. Configure API Key

Create a `.env` file in the root directory:

```env
GEMINI_API_KEY=your_gemini_api_key_here
```

> Get your API key from [Google AI Studio](https://aistudio.google.com/).

### 4. Run the Application

```bash
streamlit run app.py
```

---

## 🛠️ Tech Stack

- **Frontend / Framework:** Streamlit
- **LLM / AI:** Google Gemini API (`google-genai`)
- **Document Parsing:** PyPDF2, python-docx
- **Voice Synthesis:** gTTS (Google Text-to-Speech)

---

## 👤 Author

Developed by **Komara Prasad**
- GitHub: [@prasad-tech7](https://github.com/prasad-tech7)
