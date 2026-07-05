![Python](https://img.shields.io/badge/Python-3.11-blue)

![Gradio](https://img.shields.io/badge/Gradio-UI-orange)

![Groq](https://img.shields.io/badge/Groq-LLM-green)

![License](https://img.shields.io/badge/License-MIT-yellow)

# WisdomBot

WisdomBot is an AI-powered emotional support companion designed to provide warm, compassionate, and non-judgmental conversations for students, professionals, and anyone experiencing stress, anxiety, loneliness, or emotional overwhelm.

Unlike traditional chatbots, WisdomBot focuses on listening first and responding with empathy. It draws inspiration from the timeless wisdom of the Bhagavad Gita, Stoic philosophy, Buddhist mindfulness, and modern psychological principles to gently guide users toward clarity and emotional balance.

> **Note:** WisdomBot is an emotional support companion and is **not** a replacement for professional mental health care, therapy, or medical advice.

---

## Features

- Compassionate AI conversations
- Calm, warm, and non-judgmental responses
- Inspired by timeless wisdom and mindfulness
- Built-in emotional safety guidelines
- Crisis response with mental health helpline recommendation
- Secure API key management using environment variables
- Simple and interactive Gradio web interface
- Powered by Groq's fast LLM inference

---

## Tech Stack

- Python
- Gradio
- Groq API
- python-dotenv

---

## Project Structure

```
WisdomBot/
│── app.py
│── .env                 # Local environment variables (not uploaded)
│── .gitignore
│── requirements.txt
└── README.md
```

---

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/WisdomBot.git
cd WisdomBot
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Create a `.env` file

Create a file named `.env` in the project root.

Add your Groq API key:

```env
GROQ_API_KEY=your_groq_api_key_here
```

You can obtain an API key from:

https://console.groq.com/keys

---

## Running the Project

Start the application with:

```bash
python app.py
```

Gradio will generate a local URL in the terminal.

Open that URL in your browser to interact with WisdomBot.

---

## AI Behavior

WisdomBot is designed with the following principles:

- Listen before giving advice
- Respond with kindness and empathy
- Never judge the user's emotions
- Encourage self-reflection rather than giving commands
- Avoid therapy jargon
- Never provide harmful or unsafe guidance
- Recommend immediate human support when someone appears to be in crisis

The responses are inspired by:

- Bhagavad Gita
- Stoic Philosophy
- Buddhist Mindfulness
- Modern Psychology

Rather than quoting religious texts directly, WisdomBot expresses their underlying wisdom in simple, conversational language.

---

## Safety

WisdomBot prioritizes user safety.

If a conversation suggests that a user may be in emotional crisis, the chatbot responds with compassion and encourages them to seek immediate help from trusted people and professional support services.

For users in India, WisdomBot recommends:

**iCall Mental Health Helpline**

Phone: **9152987821**

WisdomBot does not provide medical advice, diagnosis, or treatment.

---

## Environment Variables

The project requires the following environment variable:

| Variable | Description |
|----------|-------------|
| GROQ_API_KEY | Your Groq API key |

The `.env` file is excluded from Git using `.gitignore` and should never be committed to the repository.

---

## Requirements

```
gradio
groq
python-dotenv
```

or install using:

```bash
pip install -r requirements.txt
```

---

## Screenshots

### Chat Example

![Chat](assets/chat.png)

## Future Improvements

- Conversation memory
- Mood tracking
- Voice input and speech output
- Multi-language support
- Daily mindfulness reflections
- Guided breathing exercises
- Journaling feature
- Personalized coping suggestions

---

## Disclaimer

WisdomBot is intended for emotional support and general well-being.

It is **not** a substitute for licensed mental health professionals, therapists, psychiatrists, or emergency services.

If you or someone you know is experiencing a mental health crisis, please contact local emergency services or a qualified mental health professional immediately.

---

## License

This project is intended for educational and learning purposes.
