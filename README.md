# Mini Alexa Voice Assistant

This is a simple voice assistant named "Alexa" built using Python. It can perform various tasks such as playing music, telling the time, answering questions from Wikipedia, telling jokes, and more, using voice commands.

## Features

- **Play Songs**: You can ask Alexa to play songs on YouTube.
- **Time**: Ask Alexa for the current time.
- **Wikipedia Search**: Ask Alexa "Who is [person]" to get a brief Wikipedia summary.
- **Jokes**: Alexa can tell jokes using the `pyjokes` library.
- **Friendly Interaction**: Alexa can respond to simple friend-related queries.

## Requirements

- Python 3.x
- Libraries:
  - `speech_recognition`: To capture and recognize speech.
  - `pyttsx3`: For text-to-speech conversion.
  - `pywhatkit`: To play YouTube videos.
  - `wikipedia`: To fetch information from Wikipedia.
  - `pyjokes`: To tell jokes.

You can install the required libraries using the following command:

```bash
pip install speech_recognition pyttsx3 pywhatkit wikipedia pyjokes
