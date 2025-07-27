# 🤖 AI Interview Question Generator from Resume (Gemini API + Streamlit)

A streamlined, powerful web app that leverages the **Google Gemini API (Flash or later)** to generate personalized interview questions from a resume (PDF). It extracts resume content and produces:

* ✅ 10 technical questions based on detected skills
* 💬 5 HR questions
* 🎯 3 scenario-based questions

Built with **Streamlit**, **PyMuPDF**, and the **Gemini API**.

---

## 🚀 Features

* Upload a resume in PDF format.
* Automatically extracts text using the `PyMuPDF` (fitz) library.
* Sends extracted content to Google Gemini API (Flash model or newer) via REST.
* Presents AI-generated interview questions in a clean, user-friendly Streamlit interface.
* Fast and responsive—runs locally.

---

## 📂 Project Structure

```
ai-interview-generator/
├── app.py
├── requirements.txt
└── README.md
```

---

## 🔧 Setup Instructions

### 1. Clone the Repo

```bash
git clone https://github.com/hiteshsingh01/Resume-Interview-Question-Generator.git
cd Resume-Interview-Question-Generator
```

### 2. (Optional) Create a Python Virtual Environment

```bash
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Add Gemini API Key

In `app.py`, replace the placeholder with your actual API key:

```python
API_KEY = "your-gemini-api-key-here"
```

### 5. Run the App

```bash
streamlit run app.py
```

---

## 📦 requirements.txt

```txt
streamlit
pymupdf
requests
```

---

## 🤝 Credits

* Built with ❤️ using **Google Gemini API**
* UI powered by **Streamlit**
* PDF parsing via **PyMuPDF (fitz)**

---

## 🛡️ Disclaimer

This project is intended for educational and prototyping use only. Ensure you manage your Gemini API quota responsibly and keep your API key secure.

---

## 📬 Contact

Developed by **Jayant Bhati** ([LinkedIn](https://www.linkedin.com/in/hitshsingh01/)). Have feedback or want to collaborate? Reach out!

---

