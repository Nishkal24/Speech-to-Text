Speech Recognition with Python

This project demonstrates a simple speech recognition application using Python's speech_recognition library. The program captures audio through the default microphone, processes it to handle ambient noise, and recognizes spoken words using Google's Speech Recognition API.
Table of Contents

    Features
    Prerequisites
    Setup and Installation
    Usage
    Error Handling
    Acknowledgments
    Contact

Features

    Captures audio from the default microphone.
    Adjusts for ambient noise to improve recognition accuracy.
    Converts speech to text using Google Speech Recognition API.
    Provides real-time transcription in the terminal.

Prerequisites

    Python 3.x installed on your system.
    The following Python library:
        speech_recognition

Install the library using pip:

pip install SpeechRecognition  

Setup and Installation

    Clone or Download the Repository
    Download the script file (speech_recognition.py) or copy its code.

    Install Dependencies
    Make sure the speech_recognition library is installed.

    pip install SpeechRecognition  

    Microphone Configuration
    Ensure your default microphone is properly set up on your system.

Usage

Run the script to start real-time speech recognition.
Steps:

    Open a terminal or command prompt.
    Execute the script:

    python speech_recognition.py  

    Speak into your microphone.
    The program will print the recognized text in the terminal.

Error Handling

The script handles the following exceptions:

    Ambient Noise Adjustment
        The program adjusts to ambient noise for better accuracy.

    Unknown Value Error
        If the speech cannot be understood, the script will print:

    Sorry, I could not understand the audio.  

Request Error

    If there's an issue connecting to Google's Speech Recognition service, the script will print the error message:

        Could not request results from Google Speech Recognition service; <error_message>  

Acknowledgments

This project uses:

    The SpeechRecognition Library.
    The Google Speech Recognition API for speech-to-text conversion.
