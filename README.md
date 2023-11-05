# Chat with YT

This is a Colab notebook that allows you to transcribe a short YouTube video (less than 10 minutes) using AI, and then have a conversation with an AI assistant about the content.

## Features

- Downloads audio from a YouTube video URL
- Transcribes the audio using OpenAI Whisper 
- Breaks audio into short clips for transcribing
- Compresses long transcripts to fit in chatbot memory
- Chats with an AI assistant (GPT-3.5 Turbo) about video content
- Manages chatbot memory/context

## Usage

To use this notebook:

1. Upload it to Google Colab and connect your Drive 
2. Run the cells in order to install dependencies 
3. Paste in a YouTube video URL less than 10 minutes long
4. The notebook will download and transcribe the audio
5. You can then chat with the AI assistant about the transcript
   - Simply type your questions and the assistant will respond
   - Type 'exit' to end the conversation

The transcribed text and chat logs will be saved into your Google Drive in the folder structure that is mounted.

Overall this notebook shows how AI transcription and chatbot models can be combined to have an interactive conversation about a short video, without needing to watch or read it directly.

Let me know if you have any other questions!
