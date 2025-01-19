# Voice Assistant using Python

## Description
This is a simple **Voice Assistant** built using Python. The assistant listens to your voice commands, converts them to text, and then performs actions like opening websites, searching Wikipedia, telling the time, and more.

The Voice Assistant uses several Python libraries such as **SpeechRecognition**, **pyttsx3**, and **PyAudio** to process voice commands and provide audio feedback to the user.

## Features
- **Speech Recognition**: Converts spoken words into text.
- **Text-to-Speech**: Converts the assistant's text responses into speech.
- **Wikipedia Search**: Fetches information from Wikipedia based on user queries.
- **Web Browsing**: Opens websites like Google, YouTube, etc.
- **Basic Commands**: Includes functions to tell the time, greet the user, and more.

## Technologies Used
- **SpeechRecognition**: For converting speech to text.
- **pyttsx3**: For text-to-speech conversion.
- **PyAudio**: Used by SpeechRecognition for microphone input (may need to be installed separately).
- **wikipedia**: Fetches information from Wikipedia.
- **webbrowser**: Opens websites based on user commands.
- **datetime**: Fetches current time for time-related commands.

## Prerequisites
Before running this project, you will need to install the following Python libraries:

- **SpeechRecognition**
- **pyttsx3**
- **PyAudio**
- **wikipedia**
- **webbrowser**
- **datetime**

You can install these libraries using pip:

```bash
pip install SpeechRecognition pyttsx3 pyaudio wikipedia
