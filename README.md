# 🤖 Jarvis – Voice Controlled AI Assistant (Python)

Jarvis is a **Python-based voice-controlled virtual assistant** that responds to user voice commands and performs everyday tasks such as opening websites, playing music, reading news, and answering questions using a **Large Language Model (LLM)**.

This project showcases the practical implementation of **speech recognition**, **text-to-speech**, **API integration**, and **AI-powered automation**.

---

## 🚀 Features

- 🎤 Wake word activation (**"Jarvis"**)
- 🌐 Open websites via voice commands:
  - Google
  - YouTube
  - Facebook
  - LinkedIn
- 🎵 Play songs using a custom music library
- 📰 Fetch and read live news headlines
- 🤖 Intelligent responses using an LLM (OpenAI / Gemini / Claude, etc.)
- 🔊 Voice responses using Text-to-Speech

---

## 🛠️ Technologies & Libraries Used

- **Python**
- `speech_recognition`
- `pyttsx3`
- `gTTS`
- `pygame`
- `webbrowser`
- `requests`
- **LLM API (user’s choice)**

---

## 📂 Project Structure

Jarvis/
│
├── main.py # Main voice assistant logic
├── musicLibrary.py # Songs and URLs dictionary
├── README.md # Project documentation



---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/Jarvis.git
cd Jarvis

2️⃣ Install Required Dependencies

pip install speechrecognition pyttsx3 gtts pygame requests openai pocketsphinx


🔑 API Key Configuration (Important)

This project uses a Large Language Model (LLM) to generate intelligent replies.

⚠️ You must use your own API key.
You may use any LLM provider, such as:

OpenAI (GPT models)

Google Gemini

Anthropic Claude

Any compatible LLM API

Configuration Example

Inside the aiProcess() function in main.py:

client = OpenAI(api_key="YOUR_LLM_API_KEY")


(Windows PowerShell)
setx LLM_API_KEY "your_api_key_here"


# ▶️ How to Run

python main.py

### Usage Flow

Jarvis initializes with a voice message

Say "Jarvis" to activate

Give your command

### 🎙️ Example Voice Commands

Jarvis

Open YouTube

Open LinkedIn

Play music

Tell me today’s news

What is artificial intelligence?


## 📜 License

This project is open-source and intended for learning and educational purposes.
