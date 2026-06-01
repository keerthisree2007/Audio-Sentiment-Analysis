# Audio-Based Sentiment Analysis using Whisper and Hugging Face

## Project Overview

This project performs sentiment analysis on audio input using Artificial Intelligence and Natural Language Processing (NLP) techniques.

The system accepts an audio file as input, converts the speech into text using OpenAI Whisper, analyzes the sentiment of the extracted text using a Hugging Face Transformer model, and finally converts the sentiment result into speech.

---

## Project Workflow

Audio Input
↓
Speech-to-Text (Whisper)
↓
Extracted Text
↓
Sentiment Analysis (Hugging Face DistilBERT)
↓
Positive / Negative
↓
Text-to-Speech (gTTS)
↓
Audio Output

---

## Technologies Used

### OpenAI Whisper
Used for Speech-to-Text conversion.

### Hugging Face Transformers
Used for Sentiment Analysis.

Model:
distilbert-base-uncased-finetuned-sst-2-english

### Google Text-to-Speech (gTTS)
Used to convert sentiment results into audio.

### Google Colab
Development and execution environment.

---

## Features

- Audio Upload
- Speech Recognition
- Sentiment Detection
- Confidence Score Prediction
- Audio Response Generation
- End-to-End NLP Pipeline

---

## Installation

Install required libraries:

```bash
pip install openai-whisper
pip install transformers
pip install torch
pip install gtts
