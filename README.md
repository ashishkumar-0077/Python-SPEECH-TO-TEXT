# 🎙️ Speech-to-Text Transcriber

A simple and interactive **Speech-to-Text Transcriber** built with **Streamlit** that converts recorded or uploaded audio into text using Google's Speech Recognition API. This application provides an easy-to-use interface for recording voice, uploading audio files, and generating accurate transcriptions.

---

## 🚀 Features

* 🎤 Record audio directly from the browser
* 📂 Upload audio files (`.mp3`, `.wav`, `.m4a`)
* 🔄 Automatic audio conversion to WAV format
* 📝 Convert speech into text using Google Speech Recognition
* 📋 Display transcription in a text area
* ⚡ Simple and user-friendly Streamlit interface
* ❌ Handles speech recognition and API errors gracefully

---

## 🛠️ Tech Stack

* Python 3
* Streamlit
* SpeechRecognition
* PyDub
* FFmpeg
* Google Speech Recognition API

---

## 📁 Project Structure

```
Speech-to-Text-Transcriber/
│
├── app.py
├── requirements.txt
├── translator-icon.png
├── README.md
└── assets/
```

---

## 📦 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Speech-to-Text-Transcriber.git
```

### 2. Navigate to the Project Folder

```bash
cd Speech-to-Text-Transcriber
```

### 3. Create a Virtual Environment (Optional)

```bash
python -m venv venv
```

Activate the environment

**Windows**

```bash
venv\Scripts\activate
```

**Mac/Linux**

```bash
source venv/bin/activate
```

---

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 5. Install FFmpeg

PyDub requires FFmpeg for audio conversion.

#### Windows

Download FFmpeg from:

https://ffmpeg.org/download.html

Add FFmpeg to your system PATH.

---

### 6. Run the Application

```bash
streamlit run app.py
```

---

## 📷 Application Workflow

1. Launch the Streamlit application.
2. Record your voice or upload an audio file.
3. Click the **Transcribe** button.
4. The application converts the audio into WAV format.
5. Google Speech Recognition processes the audio.
6. The transcribed text is displayed on the screen.

---

## 📚 Supported Audio Formats

* MP3
* WAV
* M4A

---

## 📄 Requirements

```
streamlit
SpeechRecognition
pydub
ffmpeg-python
```

---

## 🎯 Future Enhancements

* 🌍 Multi-language transcription
* 📥 Download transcription as TXT or PDF
* ☁️ OpenAI Whisper integration
* 🎵 Noise reduction
* ⏱️ Real-time speech transcription
* 📑 Speaker identification
* 🔊 Audio playback controls
* 🌐 Translation of transcribed text

---

## 🤝 Contributing

Contributions are welcome!

1. Fork this repository.
2. Create a feature branch.
3. Commit your changes.
4. Push to your branch.
5. Open a Pull Request.

---

## 👨‍💻 Author

**Ashish Kumar**

* 📊 Data Science Student
* 💻 Python Developer
* 📈 Data Analyst
* 📊 Power BI | SQL | Python | Machine Learning

---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.

---

## 📜 License

This project is licensed under the **MIT License**.
