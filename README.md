# 🗣️ Fryda – Python Voice Assistant

Fryda is a simple voice-controlled assistant built in Python.  
It can play YouTube videos, tell the current time/date, answer simple queries, and fetch brief information from Wikipedia — all via voice commands.

## 📌 Features
- Voice Command Recognition – Listens to user instructions via microphone.
- YouTube Playback – Plays requested songs/videos directly on YouTube.
- Time & Date Reporting – Speaks out the current time and date.
- Wikipedia Search – Fetches a one-line summary of a person or topic.
- Small Talk – Responds to greetings and personal questions.
- Text-to-Speech Responses – Speaks results using `pyttsx3`.

## 🛠️ Tech Stack
- Python 3.x
- Libraries:
  - `speech_recognition` – For speech-to-text.
  - `pyttsx3` – Text-to-speech engine.
  - `pywhatkit` – YouTube playback.
  - `wikipedia` – Fetching information.
  - `datetime` – Time and date handling.


Install required dependencies:
`pip install speechrecognition pyttsx3 pywhatkit wikipedia`

Install additional requirements for speech_recognition
Make sure you have PyAudio installed:
`pip install pyaudio`


Example Commands:
Fryda play Shape of You
Fryda time
Fryda date
Fryda how are you
Fryda what is your name
Fryda who is Elon Musk


📂 Project Structure
fryda-voice-assistant/
│── fryda.py          # Main Python script
│── README.md         # Documentation
└── requirements.txt  # Dependencies list (optional)


🚀 Future Improvements
    Add support for more commands.
    Integrate with OpenAI API for smarter conversations.
    Add weather, news, and reminder functionalities.
    Implement wake-word detection without needing "Fryda" every time.
