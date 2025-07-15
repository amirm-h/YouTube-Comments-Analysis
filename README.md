# 🎩 YouTube Comment Analyzer

As a magician, I’ve always dreamed of improving my online presence — but time has often been short. That’s why I decided to take a moment during my focus on developing my technical and academic skills to create something helpful:  
A tool that analyzes YouTube video comments by simply providing a link.

---

## 📌 About the Project

This program allows users to enter a **YouTube video link** and automatically analyzes its comments. The tool uses sentiment analysis and keyword extraction to help determine:

- What parts of the video viewers liked or disliked the most  
- Which **keywords** or **topics** were repeated or highlighted  
- Whether the general feedback is **positive**, **negative**, or **neutral**

It’s a quick way for content creators to gain insight into their audience's thoughts and feelings — without manually reading hundreds of comments.

---

## 🚀 How It Works

1. You provide a valid **YouTube video URL**
2. The app uses the **YouTube Data API** to fetch comments
3. Comments are processed using **Natural Language Processing (NLP)** techniques:
   - Sentiment analysis (Positive / Negative / Neutral)
   - Keyword extraction (most frequently mentioned words)

---

## 🔑 Getting an API Key

To use the YouTube API, you need to create your own free API key:

1. Go to [Google Cloud Console](https://console.cloud.google.com/)
2. Create a new project (or use an existing one)
3. Navigate to **APIs & Services > Library**
4. Search for **YouTube Data API v3** and enable it
5. Go to **APIs & Services > Credentials**
6. Click **+ Create Credentials > API Key**
7. Copy the key and paste it into the app’s config section or input field

---

## ⚠️ Limitations of the Free API Key

- The free YouTube API key has a **quota limit** of 10,000 units per day  
- Each request to fetch comments **costs 1 unit per comment thread**  
- So if your video has 500 top-level comments, that's 500 units per call  
- If you exceed your quota, the app will stop fetching new comments until the quota resets (every 24 hours)

---

## 🔮 Future Plans

I'm working on extending this project to support **multi-language comment analysis**, including sentiment classification and keyword extraction in other languages such as Persian, Spanish, and more.

---

## 🧠 Why This Project?

This project is part of my personal journey to merge my passion for magic with my growing expertise in programming and AI. I wanted to build something practical that reflects my evolving digital presence — while helping other creators, too.
