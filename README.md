# 🚀 Resume Analyzer Based on Job Description

This project is an AI-powered Resume Analyzer that evaluates your resume against a job description using Optical Character Recognition (OCR), Natural Language Processing (NLP), and keyword matching techniques. It calculates an ATS (Applicant Tracking System) match score and suggests the best-fit roles based on extracted skills.

## 🔍 Features

- 📄 PDF Resume Parsing using OCR (Tesseract + pdf2image)
- 🧠 Keyword Extraction from Job Descriptions
- 🛠️ Skill Matching for 10+ Tech Roles (e.g., AI/ML, Web Dev, Data Science)
- 📊 ATS Match Score Visualization with Pie Charts
- 🤖 Role Recommendations based on matched skills
- 🌐 Interactive Gradio Interface

## 🛠️ Built With

- Python
- Gradio
- Tesseract OCR
- PyMuPDF (`fitz`)
- pdf2image
- NLTK
- Matplotlib

## 📦 Installation

```bash
pip install gradio pdf2image pytesseract nltk matplotlib PyMuPDF
sudo apt-get install -y poppler-utils
```

Also ensure Tesseract is installed and accessible via PATH.

## 🚀 Usage

Run the app locally:

```bash
python resume_checker.py
```

Then open the Gradio interface to:

1. Upload a resume (PDF format).
2. Paste the job description.
3. Get ATS score, skill insights, and role suggestions.

## 💼 Supported Roles

- AI/ML Intern
- Data Analyst
- Web Developer
- Backend Developer
- Cloud Engineer
- DevOps Engineer
- Cybersecurity Analyst
- Data Scientist
- Business Analyst
- Full Stack Developer

## 📊 Example Output

- 🎯 Pie chart showing match score
- 💡 Markdown suggestions with top matching roles and improvement tips

## 📄 License

This project is licensed under the [MIT License](LICENSE).
