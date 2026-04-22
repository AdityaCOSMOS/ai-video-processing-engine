# 🎬 AI Video Processing Engine

## 🚀 Overview

An AI-powered video processing pipeline that automates common editing tasks using **Whisper (AI)** and **FFmpeg**.

The system converts raw video into a refined output by intelligently trimming, enhancing, and augmenting content based on speech understanding.

---

## ✨ Features

* 🧠 **Smart Trim (AI-Based)**
  Uses Whisper timestamps to remove non-speaking segments

* ✂️ **Silence Removal**
  Eliminates unnecessary pauses for smoother playback

* 📝 **Subtitle Generation & Styling**
  Automatically generates and burns subtitles into the video

* 🔊 **Audio Enhancement**
  Noise reduction and loudness normalization

* 🎨 **Color Correction**
  Improves brightness, contrast, and saturation

* 🖼️ **Thumbnail Extraction**
  Extracts a representative frame from the final video

* 📊 **Processing Report**
  Generates a summary of transformations applied

---

## 🧱 Tech Stack

* **Python**
* **FFmpeg**
* **OpenAI Whisper**
* **Google Colab**

---

## ⚙️ How It Works

1. Upload video to Google Drive
2. Select processing features
3. Pipeline executes selected modules sequentially
4. Final video, thumbnail, and report are generated

---

## 🧪 Example Input

```bash
1 3 4 6
```

---

## 📂 Output

```text
output/
├── final_video.mp4
├── processing_report.txt
└── thumbnail.jpg
```

---

## 🧠 Key Idea

AI (Whisper) converts unstructured audio into structured timestamps, which are then used to guide deterministic video processing operations using FFmpeg.

---

## 🎯 Learning Outcomes

* Integration of AI with traditional media processing
* Modular pipeline design
* Handling real-world issues like file management and processing order

---

## 🚀 Future Improvements

* Web-based UI
* Real-time processing
* Advanced scene detection
* AI-based thumbnail selection

---

## 👨‍💻 Author

Aditya Yadav

Gauri Dadhich
