# SPEACHTOTXT – Voice Registration System

An intuitive, interactive Speech-to-Text (STT) web application designed for fast and hands-free attendee registration (such as for medical and doctor conferences).

## 🚀 Features

- **Hands-Free Voice Input**: Powered by the Web Speech Recognition API (`SpeechRecognition` / `webkitSpeechRecognition`).
- **Interactive Speech Synthesis**: Audio guidance and confirmations using the Web Speech Synthesis API (`speechSynthesis`).
- **Smart Formatting**:
  - Automatically capitalizes names and strips conversational prefixes (e.g., "my name is", "I am").
  - Intelligently converts spoken numbers (words like "nine", "double five", "oh") into clean numeric phone numbers.
- **Local Persistence**: Saves registrations locally in browser `localStorage`.
- **CSV Export**: Easily download all registered attendees as a `.csv` spreadsheet file with one click.
- **Adaptive UI**: Built with a responsive, modern interface supporting both Light and Dark modes.

## 🛠️ Getting Started

### 1. Direct Browser Usage
Simply open [index.html](index.html) or [Voice Registration – Doctors Conference.html](Voice%20Registration%20%E2%80%93%20Doctors%20Conference.html) in any modern Chromium-based browser (such as Google Chrome, Microsoft Edge, or Brave).

### 2. Microphone Permissions
- Ensure you grant microphone permissions when prompted by your browser.
- Voice recognition operates best in a clear audio environment.

## 📋 Technology Stack
- **HTML5 & CSS3**: Vanilla CSS with custom properties, safe-area insets, and dark-mode adaptation.
- **JavaScript (ES6+)**: Web Speech API (Recognition + Synthesis) & client-side CSV generator.

## 📄 License
MIT License.
