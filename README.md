

# 🎙️ VoiceCraft - Web Text-to-Speech App

**VoiceCraft** is a simple, elegant web application that converts user input into natural-sounding speech using AI-powered voice models from Pollinations. Built in PHP and JavaScript, the app offers seamless voice selection and instant MP3 audio playback/download — all in your browser.

🌐 Live Demo: [https://kriztech.in/bots/voice](https://kriztech.in/bots/voice)  
👨‍💻 Created by: [Kriztech](https://kriztech.in)  
🤖 Powered by: [Pollinations AI](https://pollinations.ai)

---

## 🚀 Features

- 🔊 **Instant AI voice generation** via Pollinations (GET API)
- 🎭 **Multiple voice models** to choose from (Alloy, Echo, Fable, Nova, Shimmer, etc.)
- 💡 **User-friendly interface** with clean layout and fast performance
- 🎧 **Audio playback & download** supported
- ⚙️ **Lightweight & responsive** — runs smoothly on all modern browsers
- 💬 Built with **PHP, HTML, CSS & JavaScript**

---

## 🧪 How It Works

VoiceCraft uses the Pollinations text-to-speech API:
```
GET https://text.pollinations.ai/{prompt}?model=openai-audio&voice={voice}
```

Where:
- `prompt` = Your input text (auto-encoded)
- `voice` = Selected voice model (optional, defaults to "alloy")

Supported Voices:
- `alloy`
- `echo`
- `fable`
- `nova`
- `onyx`
- `shimmer`

---

## 📂 Folder Structure

```
/bots/voice/
├── index.php        # Main app file
├── style.css        # Custom styling
├── script.js        # Handles frontend logic (API calls, playback)
├── assets/          # Icons and sound assets
└── README.md        # You are here
```

---

## 🛠️ Installation

1. **Clone this repository:**
   ```bash
   git clone https://github.com/yourusername/voicecraft-web.git
   ```

2. **Upload to your PHP-enabled server.**

3. **Access it via your browser:**
   ```
   https://yourdomain.com/bots/voice/
   ```

---

## 📸 Screenshots

_You can add screenshots here showing voice selection and audio output._

---

## 🤝 Credits

- AI Voice API: [Pollinations AI](https://pollinations.ai)
- App built by [Kriztech](https://kriztech.in)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).


---

Let me know if you'd like me to generate badges (e.g., "Built with PHP", "Live Demo"), preview image banners, or markdown-ready screenshots.
