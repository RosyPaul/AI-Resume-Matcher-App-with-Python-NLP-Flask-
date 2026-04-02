# 🤖 AI Resume Matcher App

An AI-powered resume matching tool built with Python, NLP, and Flask. Upload multiple resumes and a job description, and the app will rank the top 5 most suitable candidates using TF-IDF vectorization and cosine similarity.

---

## 🚀 Live Demo

> https://ai-resume-matcher-app-with-python-nlp.onrender.com

---

## 📌 Features

- Upload multiple resumes (PDF, DOCX, TXT)
- Paste any job description
- Automatically extracts and analyzes resume text
- Ranks top 5 matching resumes using NLP
- Simple and clean web interface

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Backend | Python, Flask |
| NLP | scikit-learn (TF-IDF, Cosine Similarity) |
| File Parsing | PyPDF2, docx2txt |
| Frontend | HTML, CSS (Jinja2 Templates) |
| Deployment | Render |


---

## 📁 Project Structure
AI-Resume-Matcher/
├── templates/
│   └── matches_resume.html
├── uploads/
├── main.py
├── requirements.txt
├── Procfile
├── .gitignore
└── README.md

## ⚙️ How It Works

1. User uploads one or more resumes (PDF/DOCX/TXT)
2. User pastes a job description
3. App extracts text from all uploaded files
4. TF-IDF vectorizer converts text into numerical vectors
5. Cosine similarity is calculated between the job description and each resume
6. Top 5 matching resumes are returned with similarity scores

---

## 🧪 Running Locally

1. Clone the repository
git clone https://github.com/RosyPaul/AI-Resume-Matcher-App-with-Python-NLP-Flask-.git
cd AI-Resume-Matcher-App-with-Python-NLP-Flask-

2. Install dependencies
pip install -r requirements.txt

3. Run the app
python main.py

4. Open in browser
http://localhost:5000

---

## 📦 Requirements

flask
docx2txt
PyPDF2
scikit-learn

---

## 🌐 Deployment

This app is deployed on Render. To deploy your own instance:
1. Push your code to GitHub
2. Go to render.com and create a new Web Service
3. Connect your GitHub repo
4. Set build command: pip install -r requirements.txt
5. Set start command: python main.py
6. Deploy!

---

## 📄 License

This project is licensed under the Apache License 2.0.

---

## 🙋‍♀️ Author

Rosy Paul
GitHub: https://github.com/RosyPaul
