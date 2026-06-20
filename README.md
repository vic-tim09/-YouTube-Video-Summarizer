# YouTube-Video-Summarizer

A Python-based AI project that automatically generates concise summaries of YouTube videos using video transcripts and the Llama Large Language Model through the Groq API.

## 📌 Project Overview

Watching long YouTube videos can be time-consuming. This project extracts the transcript from a YouTube video and uses Generative AI to create a short, meaningful summary of the content.

The user simply provides a YouTube video URL, and the system generates a summary within seconds.

---

## ✨ Features

- Extracts Video ID from YouTube URLs
- Fetches video transcript automatically
- Supports long educational videos
- Generates AI-powered summaries
- Simple and beginner-friendly implementation
- Built inside Jupyter Notebook

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- YouTube Transcript API
- Google Gemini API
- Regular Expressions (Regex)
- Environment Variables (.env)

---

## 📂 Project Workflow

## 📂 Project Workflow

1. User enters a YouTube video URL.
2. Video ID is extracted from the URL.
3. Transcript is fetched using YouTube Transcript API.
4. Transcript text is combined into a single document.
5. The transcript is sent to the Llama model through the Groq API.
6. An AI-generated summary is returned and displayed.

---

## 📦 Required Libraries

```bash
pip install youtube-transcript-api
pip install groq
pip install python-dotenv
```

Or install all dependencies using:

---
## 🔮 Future Improvements

- Streamlit Web Application
- Multi-language Summaries
- PDF Export
- Bullet Point Summaries
- Hindi Summary Generation
- Video Title and Thumbnail Fetching

---

## 🎯 Learning Outcomes

Through this project, I learned:

## 🎯 Learning Outcomes

Through this project, I learned:
- API Integration
- Working with Large Language Models (LLMs)
- Groq API Usage
- Prompt Engineering
- Text Processing
- Environment Variables
- YouTube Transcript Extraction
- Jupyter Notebook Development

---
