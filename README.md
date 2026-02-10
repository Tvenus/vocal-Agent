# Real-Time Cascading Speech-to-Speech Chatbot

A real-time cascading speech-to-speech chatbot that combines advanced speech recognition, AI reasoning, and neural text-to-speech capabilities. Built for seamless voice interactions with web integration and extensible tool system.

## Features

- **Real-time Speech Recognition** - Powered by Whisper + Silero VAD for accurate voice input
- **Intelligent AI Reasoning** - Multimodal reasoning with Llama 3.1 8B through Agno agent
- **Web Integration** - Access to Google Search, Wikipedia, and Arxiv for real-time information
- **Natural Voice Synthesis** - High-quality voice output using Kokoro-82M ONNX
- **Low-latency Processing** - Optimized audio pipeline for responsive interactions
- **Extensible Tool System** - Easy to add new capabilities to the agent
- **Cross-platform Support** - Works on macOS, Linux, and Windows

## 🛠️ Tech Stack

| Component | Technology | Description |
|-----------|------------|-------------|
| **Speech-to-Text** | Whisper (large-v1) + Silero VAD | Real-time transcription with voice activity detection |
| **Language Model** | Llama 3.1 8B via Ollama | Local AI reasoning and conversation |
| **Text-to-Speech** | Kokoro-82M ONNX | Natural voice synthesis |
| **Agent Framework** | Agno LLM Agent | Extensible tool-calling capabilities |
| **Audio Processing** | SoundDevice + SoundFile | Real-time audio I/O |

## Prerequisites

- **Python 3.9+**
- **Ollama** - Local LLM server
- **espeak-ng** - Text-to-speech engine
- **Microphone and Speakers** - For voice interaction

