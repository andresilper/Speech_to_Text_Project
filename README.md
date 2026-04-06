# Audio Transcription and Word Export with Whisper

## Overview
This project allows you to **record audio**, **transcribe speech to text** using [OpenAI Whisper](https://github.com/openai/whisper), and **save the transcription into a Word document** (`.docx`).  
It is designed to help researchers, students, and professionals quickly convert spoken content into written text and organize it into a structured document.

---

## Features
-  Record audio from your microphone
-  Transcribe speech using Whisper (`small` model by default)
-  Support for multiple languages (default: Portuguese `"pt"`)
-  Save transcriptions directly into a Word file (`my_book.docx`)
-  Append new transcriptions to the same document, building a "book" over time

---

## Requirements
Install dependencies with:

```bash
pip install -r requirements.txt
