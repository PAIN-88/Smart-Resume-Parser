
# 🧠 Resume Screening & Shortlisting System

An AI-powered web application that helps recruiters automatically **analyze, extract, and shortlist candidate resumes** based on their skills, experience, and qualifications.

---

## 🚀 Features

* 🗂 **Resume Upload & Parsing** — Upload `.pdf` or `.docx` resumes.
* 🧾 **Automatic Information Extraction** — Extracts **name, contact info, skills, education, and experience** using **spaCy** NLP.
* 🧠 **Skill Matching** — Compares candidate skills with job requirements.
* 📊 **Dashboard View** — Displays all candidate data in an organized table.
* 💾 **Data Storage** — Stores parsed resume data for future access and filtering.

---

## 🏗️ Tech Stack

| Category        | Technologies Used                |
| --------------- | -------------------------------- |
| **Frontend**    | HTML, CSS,
| **Backend**     | Flask (Python)                   |
| **Database**    |                                  |
| **NLP Library** | spaCy, python-docx, PyPDF2       |
| **Environment** | Python 3.13+                     |

---

## ⚙️ Installation Guide

### 1️⃣ Clone the repository

```bash
git clone https://github.com/yourusername/resume-shortlisting-system.git
cd resume-shortlisting-system
```

### 2️⃣ Create a virtual environment

```bash
python -m venv venv
venv\Scripts\activate  # For Windows
source venv/bin/activate  # For Linux/Mac
```

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

If `requirements.txt` is not available, install manually:

```bash
pip install flask spacy python-docx PyPDF2
python -m spacy download en_core_web_sm
```

### 4️⃣ Run the application

```bash
python app.py
```

Then open your browser and go to:

```
http://127.0.0.1:5000/
```

---

## 🧩 Folder Structure

```
📁 collegeProject/
│
├── app.py                 # Main Flask app
├── resume_parser.py       # Resume parsing logic using spaCy
├── templates/             # HTML files
├── static/                # CSS, JS, images
├── uploads/               # Uploaded resumes
└── database/              # SQLite DB (if used)
```

---

## 💡 How It Works

1. Recruiter uploads one or more resumes.
2. spaCy extracts candidate details like **skills**, **education**, and **experience**.
3. Data is structured and stored in the database.
4. Recruiter can **search, sort, and shortlist** candidates easily.

---

## 🧠 Example Use Case

> Recruiters face difficulty managing hundreds of resumes — this tool automates extraction and sorting, saving time and reducing manual errors.

---

## 🤝 Contributors

* **Sudhanshu Tripathi** 
* **Priyanshu Pandey** 
* **Vivek Maurya** 
* **Rishabh Dikshit** 

---

## 📜 License

This project is licensed under the **MIT License** — free to use and modify.

---

Would you like me to make a matching `requirements.txt` file for it (so you can upload both to GitHub)?
