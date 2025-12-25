# Audio Transcription Web Application

## Overview
A web application for audio transcription supporting both English and Japanese, 
with automatic summarization for English audio.

## Tech Stack
- Python, Flask
- WhisperX for speech recognition and alignment
- Transformers (Hugging Face) for summarization
- PyTorch for model computation

## Features
- Upload audio files and perform transcription
- Supports both English and Japanese transcription
- Automatic summarization for English audio

## Contribution
Primary developer:
- Designed and implemented the transcription pipeline
- Integrated WhisperX models for ASR, alignment, and diarization
- Implemented language-specific handling for English and Japanese
- Added summarization using Hugging Face Transformers
- Developed Flask web interface for user interaction

## Security / Notes
- Provide your own Hugging Face access token
