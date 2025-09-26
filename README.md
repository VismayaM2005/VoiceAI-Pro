# 🎤 AI Voice Q&A Assistant

> Voice-powered Q&A system using AI speech recognition and intelligent response generation.

## Features
- **Voice Input**: Speak your questions naturally
- **AI Speech Recognition**: Powered by OpenAI Whisper
- **Smart Answers**: Uses Google FLAN-T5 model
- **Web Interface**: Clean, responsive design

## Tech Stack
- Python Flask
- OpenAI Whisper (Speech-to-Text)
- Google FLAN-T5 (Q&A)
- HTML/CSS/JavaScript

## Setup

1. **Clone the project**
```bash
git clone <repo-url>
cd ai-voice-qa-assistant
```

2. **Install dependencies**
```bash
pip install flask transformers torch requests numpy sounddevice soundfile python-dotenv
```

3. **Add your API token**
Create `.env` file:
```
HF_API_TOKEN=your_huggingface_token_here
```

4. **Run the app**
```bash
python voice_chat_assistant.py
```

Open `http://localhost:5000` in your browser.

## Usage
1. Click "Ask Question" button
2. Speak your question when prompted
3. Get AI-generated answer instantly

## Project Structure
```
├── voice_chat_assistant.py    # Main Flask app
├── templates/
│   └── index.html            # Web interface
└── README.md
```

## Requirements
- Python 3.8+
- Microphone access
- Internet connection
- Hugging Face API token (free)

## Demo
Ask questions like:
- "What is machine learning?"
- "How does photosynthesis work?"
- "Explain quantum computing"

---
