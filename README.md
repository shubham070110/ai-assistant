# pip install pyaudio

# ai-assistant
🧠 Chotu - Voice Assistant in Python Chotu is a voice-activated desktop assistant built using Python. It can perform everyday tasks like searching Wikipedia, opening websites, playing music, telling the time, and sending emails—all through voice commands.
Absolutely! Here's a full **`README.md`** tailored for your current voice assistant project (`Chotu`) based on the latest code you shared:

---

````markdown
# 🧠 Chotu - A Simple Python Voice Assistant

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Status](https://img.shields.io/badge/Status-Working-brightgreen)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

**Chotu** is a Python-based desktop voice assistant that listens to your voice commands and performs tasks like searching Wikipedia, playing music, opening websites, telling the time, and sending emails. It uses speech recognition and text-to-speech to interact with users in real-time.

---

## 🔧 Features

- 🔊 Text-to-speech (TTS) with `pyttsx3`
- 🎙️ Voice command input via `speech_recognition`
- 📚 Wikipedia search and spoken results
- 🌐 Opens common websites (Google, YouTube, Stack Overflow)
- 🎵 Plays music from a local directory
- ⏰ Tells current system time
- 📧 Sends emails via Gmail SMTP

---

## 🛠 Requirements

Install the required Python packages:

```bash
pip install pyttsx3 speechRecognition wikipedia
````

> **Note:** You may need to manually install `PyAudio` for Windows. Download the appropriate `.whl` file from [here](https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyaudio) and install it with:

```bash
pip install path_to_downloaded_whl_file
```

---

## 🚀 How to Run

1. Clone this repository:

```bash
git clone https://github.com/yourusername/chotu-voice-assistant.git
cd chotu-voice-assistant
```

2. Run the assistant script:

```bash
python assistant.py
```

3. Speak your commands! Try saying:

* `"Wikipedia Virat Kohli"`
* `"Open YouTube"`
* `"Play music"`
* `"What is the time?"`
* `"Email to Shubham"`

---

## ⚠️ Important Note

The current script **contains hardcoded email credentials**, which is **insecure**. Please replace this with a safer method like environment variables or a `.env` file using `python-dotenv`.

```python
# .env (DO NOT COMMIT THIS FILE)
EMAIL_USER=your_email@gmail.com
EMAIL_PASS=your_app_password
```

---

## 📌 To-Do

* [ ] Replace hardcoded email credentials with environment variables
* [ ] Add GUI using `tkinter` or `PyQt5`
* [ ] Add weather info or jokes with an API
* [ ] Add "exit" voice command
* [ ] Improve NLP with a library like spaCy or transformers

---

## 👨‍💻 Author

**Shubham Sharma**
📧 Email: `shubhamsharma.gopal@gmail.com`

---

## 📄 License

This project is licensed under the MIT License.

```

---

