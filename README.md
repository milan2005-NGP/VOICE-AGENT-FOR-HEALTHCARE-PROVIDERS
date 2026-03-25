# 🎙️ Voice Agent for Healthcare Providers

![Status](https://img.shields.io/badge/Status-Active-success.svg)
![AI Model](https://img.shields.io/badge/NLP-MedBERT--v2-blue.svg)
![Domain](https://img.shields.io/badge/Domain-HealthTech-orange.svg)
![Feature](https://img.shields.io/badge/Feature-Conversational_AI-purple.svg)

## 📌 Project Overview
The **Voice Agent for Healthcare Providers** is an AI-powered conversational portal designed to streamline administrative workflows for medical clinics. By automating routine inquiries—such as checking claim statuses or verifying patient eligibility—this tool drastically reduces call center volume and administrative burden.

The application features a real-time dashboard that tracks live conversational telemetry, verifies provider credentials (NPI), extracts patient context, and utilizes domain-specific NLP (MedBERT-v2) for highly accurate intent matching.

## 📸 Application Dashboard
![Voice AI Portal](images/voice-agent-ui.png) *(Note: Create an `images` folder in your repo, upload your screenshot there, and update this link!)*

## ✨ Key Features
* **Intelligent Intent Matching:** Leverages `MedBERT-v2` to accurately understand and route complex provider queries (e.g., "Check claim status" -> 92.5% Match).
* **Live Telemetry & Analytics:** Real-time tracking of:
  * Automatic Speech Recognition (ASR) Confidence
  * Caller Sentiment Analysis (Positive, Neutral, Negative)
  * System Latency (ms)
* **Automated Context Extraction:** Automatically detects and displays Caller Profiles (NPI, Auth Level) and Patient Context (Member ID, DOB, Plan Type).
* **Multimodal Input:** Supports both voice (microphone input) and text-based queries.

## 🛠️ Technologies Used
* **NLP / AI Engine:** [MedBERT-v2 / Hugging Face Transformers]
* **Speech-to-Text (ASR):** [OpenAI Whisper / Google Speech API / Web Speech API - *Update based on your stack*]
* **Frontend UI:** [React / Next.js / HTML5 & CSS3 -*]
* **Backend:** [Python, FastAPI / Flask, WebSockets for real-time data]

