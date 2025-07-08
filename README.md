# 🎙️ Audio to Text Transcription Tool

This Python script converts speech from a large `.mp3` or `.wav` audio file into text using **Google Speech Recognition API**. It's ideal for transcribing lectures, podcasts, or interviews into written text.

---

## ✅ Features

- 📂 Supports MP3 and WAV audio files
- ✂️ Splits long audio into smaller chunks based on silence
- 🗣️ Uses Google's Speech Recognition to transcribe each chunk
- 📄 Outputs the complete transcribed text
- 🧪 Automatically handles unrecognized segments gracefully

---

## 🧰 Requirements

- Python 3.x
- Libraries: `speechrecognition`, `pydub`, `ffmpeg`

Install required packages using:

    pip install SpeechRecognition pydub

## 🚀 How to Use
1. Upload Your Audio File
Use the files.upload() method to upload an .mp3 file.

2. Convert to WAV (if needed)
The script converts .mp3 to .wav automatically using ffmpeg.

3. Transcribe Audio
The script splits the audio into chunks where there's silence and uses Google's API to transcribe each chunk.

4. Output
Transcriptions for each chunk will be printed, followed by the full text.    
