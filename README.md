# Virtual Assistant: PDF-to-Speech Web App

A Flask-based web application that allows users to upload a PDF file, extract its text, and convert it to human-like speech. This project leverages PyMuPDF for PDF text extraction and gTTS (Google Text-to-Speech) for generating audio, making it a handy tool for anyone who prefers to listen rather than read.

## Features

- **PDF Upload:** Easily upload any PDF file via a simple web interface.
- **Text Extraction:** Automatically extracts text from the uploaded PDF using PyMuPDF.
- **Text-to-Speech Conversion:** Converts extracted text to speech with gTTS.
- **Audio Playback & Download:** Listen to the generated audio directly in the browser or download it as an MP3 file.
- **User-Friendly Interface:** Built with Flask for easy deployment and use.

## Technologies Used

- **Python 3.x**
- **Flask** – Web framework
- **PyMuPDF** – For PDF text extraction
- **gTTS** – Google Text-to-Speech for audio conversion
- **HTML/CSS** – For the front-end interface

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/virtual-assistant-pdf-to-speech.git
   cd virtual-assistant-pdf-to-speech
