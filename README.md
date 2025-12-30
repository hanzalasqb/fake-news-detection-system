# Fake News Detector (MVP)

An AI-powered Fake News Detection web application that classifies news content as **REAL** or **FAKE** using machine learning techniques.  
The system supports **text input**, **URL analysis**, and **RSS feed monitoring**, providing confidence scores and maintaining a full classification history.

This project was developed as a **class MVP** using **FastAPI** for the backend and **React** for the frontend.

---

## 🚀 Features

- 📝 **Text Classification**
  - Paste full news articles and classify them instantly.
- 🔗 **URL Classification**
  - Analyze live news article URLs.
- 📡 **RSS Feed Monitoring**
  - Add and monitor RSS feeds (e.g., CNN, GEO News).
  - Automatically fetch and analyze new articles.
- 📊 **Confidence Scoring**
  - Displays prediction confidence percentage.
- 🕒 **Classification History**
  - Stores all past classifications with timestamp.
- 🌗 **Dark / Light Mode**
  - User-friendly modern UI.
- ⚡ **FastAPI Backend**
  - High-performance REST API.
- ⚛️ **React Frontend**
  - Responsive and interactive UI.

---

## 🧠 How It Works

1. User submits **text**, **URL**, or **RSS feed**
2. Backend extracts article content
3. Text is processed by the ML classification pipeline
4. Prediction result:
   - **Label**: REAL / FAKE
   - **Confidence Score**
5. Result is stored in the database
6. History can be reviewed anytime

---

## 🏗️ Tech Stack

### Frontend
- React
- HTML5 / CSS3
- JavaScript (ES6+)

### Backend
- FastAPI
- Python 3.12
- Uvicorn

### Machine Learning
- NLP-based text classification model
- Probability-based confidence estimation

### Database
- SQLite (default, easy setup)
- Can be extended to PostgreSQL / MySQL

---

## 📁 Project Structure


