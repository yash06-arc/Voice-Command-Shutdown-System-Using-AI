# AI-Powered Voice Command Shutdown System

![Project Banner](https://img.shields.io/badge/AI-VoiceCommand-blue) ![Python](https://img.shields.io/badge/Python-3.11-green) ![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

A hands-free system that allows users to shutdown their computer using voice commands. This project demonstrates the integration of Artificial Intelligence (AI) with practical computing tasks to automate system operations efficiently.

---

## Table of Contents

- [Introduction](#introduction)  
- [AI Integration](#ai-integration)  
- [Tools and Libraries](#tools-and-libraries)  
- [Implementation](#implementation)  
- [Key Features](#key-features)  
- [Challenges](#challenges)  
- [Conclusion](#conclusion)  
- [License](#license)  
- [Contact](#contact)  

---

## Introduction

The **AI-Powered Voice Command Shutdown System** is designed to simplify the process of shutting down a computer. By speaking specific commands such as `"shutdown"` or `"turn off"`, users can trigger the system to perform a shutdown without physically interacting with the computer.  

This system is particularly useful for:

- Users seeking **hands-free operation**.  
- Individuals with **mobility challenges or disabilities**.  
- Demonstrating **AI integration in everyday computing tasks**.

---

## AI Integration

### AI Component: Speech Recognition

- The system leverages AI-based **speech recognition** to process voice input.  
- Recognizes predefined commands like `"shutdown"` or `"turn off"`.  
- Executes the shutdown automatically once the command is validated.

### Role of AI

- **Natural Language Understanding:** Converts spoken words into text commands.  
- **Command Matching:** Identifies actionable instructions.  
- **Automation:** Triggers system shutdown once the command is confirmed.

---

## Tools and Libraries

### Voice Recording
- `sounddevice` – Record audio via the system microphone.  
- `numpy` – Handle audio data as arrays.  
- `scipy.io.wavfile` – Read/write WAV files.

### Shutdown Command Recognition
- `resemblyzer` – Extracts voice embeddings for processing.  
- `os` – Executes system-level shutdown commands.  
- Optional enhancements:  
  - `speech_recognition` – Advanced speech-to-text recognition.  
  - `pyttsx3` – Audio feedback for commands.

---

## Implementation Steps

1. **Capture Voice Input**  
   - Activate the microphone to listen to user commands.

2. **Convert Speech to Text**  
   - AI-powered tool transforms spoken words into text.

3. **Check for Command**  
   - Compare recognized text with predefined shutdown commands.  
   - Proceed only if a valid command is detected.

4. **Execute Shutdown**  
   - Send a system shutdown signal using Python's `os` module.  

---

## Key Features

- **Hands-Free Convenience:** Operates without manual input.  
- **Accessibility:** Assists users with disabilities or limited mobility.  
- **Modern Interface:** Demonstrates AI-driven, voice-based interaction.  
- **Intelligent Automation:** Integrates AI with system-level operations.

---

## Challenges Faced

- Handling **background noise** effectively.  
- Recognizing **different accents and pronunciations**.  
- Preventing **accidental shutdowns** triggered by similar-sounding words.

---

## Conclusion

This project is a **simple yet powerful demonstration of AI application in everyday tasks**. By combining speech recognition with system-level commands, it automates shutdown procedures, enhances accessibility, and provides a glimpse into the future of AI-powered interfaces.

---

## License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---

## Contact

**Yashwanth HS**  
Email: [yashwanth285@gmail.com](mailto:yashwanth285@gmail.com)  
GitHub: [https://github.com/yash06-arc](https://github.com/yash06-arc)
