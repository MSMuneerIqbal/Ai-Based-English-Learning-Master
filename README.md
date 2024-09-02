# AI Based English Speaking Practice Bot

## Overview

Welcome to **SpeakBuddy**! This application offers three main features to help you practice and improve your English skills:

1. **Pronunciation Helper**: Convert text to speech and listen to the correct pronunciation.
2. **Conversation Practice**: Record your voice and receive feedback on grammar and vocabulary.
3. **Synonym Finder**: Find synonyms for a given word in English and Urdu.

## Features

- **Pronunciation Helper**:
  - Enter text and generate an audio file that pronounces the text.
  - Ideal for practicing pronunciation and listening.

- **Conversation Practice**:
  - Record your voice to get detailed feedback on grammar and vocabulary.
  - Uses advanced models for real-time transcription and feedback.

- **Synonym Finder**:
  - Enter a word to receive its synonyms in English.
  - Translates these synonyms into Urdu for better understanding.

## Models and Libraries

The application uses several powerful models and libraries:

- **[Gradio](https://www.gradio.app/)**: An easy-to-use interface library for creating interactive web applications. It allows seamless integration of machine learning models with user-friendly UIs.

- **[gTTS (Google Text-to-Speech)](https://pypi.org/project/gTTS/)**: A Python library and CLI tool to extract the spoken text from videos or audios using Google's Text-to-Speech API.

- **[Whisper](https://github.com/openai/whisper)**: A general-purpose speech recognition model developed by OpenAI, used for transcribing spoken language into text.

- **[Groq](https://www.groq.com/)**: A high-performance AI platform that provides API access to Llama3, a model used for generating detailed feedback on grammar and vocabulary.

- **[NLTK (Natural Language Toolkit)](https://www.nltk.org/)**: A library for working with human language data (text), providing tools for text processing and linguistic data analysis.

- **[Deep Translator](https://pypi.org/project/deep-translator/)**: A Python library for translation using various translation engines, including Google Translate.

## How to Use
1. **Pronunciation Helper**:
   - Go to the "Pronunciation" tab.
   - Enter your text in the provided textbox.
   - Click "Check Pronunciation" to get the audio output.

2. **Conversation Practice**:
   - Go to the "Conversation Practice" tab.
   - Record your voice using the microphone button.
   - Get real-time feedback on your speech.

3. **Synonym Finder**:
   - Go to the "Synonym Finder" tab.
   - Enter a word to see its English and Urdu synonyms.

## Setup

### Requirements

Ensure you have the following Python packages installed. You can install them using `pip`:

```bash
pip install gradio gTTS whisper groq numpy librosa nltk deep-translator

