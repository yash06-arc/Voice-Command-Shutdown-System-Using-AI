# AI-Powered Voice Command Shutdown System

![Python](https://img.shields.io/badge/Python-3.11-green) ![License](https://img.shields.io/badge/License-MIT-blue) ![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

A hands-free system that allows users to shutdown their computer using voice commands. Demonstrates AI integration with practical computing tasks.

---

## Table of Contents

- [Introduction](#introduction)  
- [AI Integration](#ai-integration)  
- [Tools and Libraries](#tools-and-libraries)  
- [Implementation](#implementation)  
- [Key Features](#key-features)  
- [Challenges](#challenges)  
- [Setup](#setup)  
- [Demo](#demo)  
- [License](#license)  
- [Contact](#contact)  

---

## Introduction

The **AI-Powered Voice Command Shutdown System** simplifies shutting down a computer. Speak commands like `"shutdown"` or `"turn off"` to trigger a shutdown automatically.  

**Ideal for:**  
- Hands-free operation  
- Users with mobility challenges  
- Demonstrating AI integration in practical tasks

---

## AI Integration

- **Speech Recognition:** AI listens to voice commands and converts speech to text.  
- **Command Matching:** Validates whether the text matches predefined shutdown phrases.  
- **Automation:** Executes system shutdown once validated.

---

## Tools and Libraries

- `sounddevice` – Record audio via microphone  
- `numpy` – Handle audio data  
- `scipy.io.wavfile` – Read/write WAV files  
- `resemblyzer` – Extract voice embeddings  
- `os` – Execute system shutdown commands  
- Optional: `speech_recognition`, `pyttsx3` for enhanced recognition and audio feedback

---

## Implementation Steps

1. **Capture Voice Input** via microphone  
2. **Convert Speech to Text** using AI-based recognition  
3. **Check Command** against predefined phrases  
4. **Execute Shutdown** using system commands

---

## Key Features

- Hands-free convenience  
- Accessibility for users with disabilities  
- Modern AI-driven interface  
- Intelligent automation

---

## Challenges

- Handling background noise  
- Recognizing different accents  
- Avoiding accidental shutdowns

---

## Setup

### Clone Repository
```bash
git clone https://github.com/yash06-arc/VoiceShutdown.git
cd VoiceShutdown
