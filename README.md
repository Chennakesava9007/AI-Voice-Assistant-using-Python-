
# AI Voice Assistant using Python 🎙️🤖

This project is a simple yet functional AI voice assistant developed in Python. It uses voice commands to perform tasks such as searching Wikipedia, telling jokes, telling the current time, and opening websites like YouTube and Google. The assistant can also be controlled via typed input if a microphone is unavailable.

## 🚀 Features

- 🎤 Voice recognition with `SpeechRecognition`
- 🗣️ Text-to-speech responses using `pyttsx3`
- 🌐 Wikipedia search and response
- 📺 Open websites like Google and YouTube
- ⏰ Tells current time
- 😂 Tells random jokes
- 🧠 Option to use microphone or keyboard input
- 🛑 Exit command to quit assistant

## 🛠️ Technologies Used

- Python
- [SpeechRecognition](https://pypi.org/project/SpeechRecognition/)
- [pyttsx3](https://pypi.org/project/pyttsx3/)
- [Wikipedia](https://pypi.org/project/wikipedia/)
- [pyjokes](https://pypi.org/project/pyjokes/)

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/AI-Voice-Assistant-Python.git
   cd AI-Voice-Assistant-Python
   ```

2. Install required libraries:
   ```bash
   pip install SpeechRecognition pyttsx3 wikipedia pyjokes
   ```

3. (Optional) Install additional dependencies for microphone support:
   - Windows: Install `pyaudio` using wheel from [PyAudio downloads](https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyaudio)
   - macOS/Linux: `brew install portaudio` or `sudo apt install portaudio19-dev && pip install pyaudio`

## 🧠 Usage

Run the assistant using:
```bash
python assistant.py
```

> If microphone access doesn't work or isn't available, modify `run_assistant(use_microphone=False)` to use text input instead.

## 📌 Example Commands

- "Search Albert Einstein on Wikipedia"
- "Open YouTube"
- "Tell me a joke"
- "What's the time?"
- "Open Google"
- "Bye" / "Exit"

## 👨‍💻 Author

**Siddavatam Chenna Kesava Reddy**  
📧 chennakesava9007@gmail.com  
[GitHub](https://github.com/Chennakesava9007) 

## 📜 License

This project is licensed under the MIT License - feel free to use and modify.
