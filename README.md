<div align="center">

# 🤖 AI Resume Analyzer using n8n & Groq

### An AI-powered Resume Analyzer that evaluates PDF resumes, calculates an ATS score, identifies strengths and weaknesses, and stores every analysis in Google Sheets.

<p>

![n8n](https://img.shields.io/badge/n8n-Workflow%20Automation-FF6D5A?style=for-the-badge&logo=n8n&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-LLM-000000?style=for-the-badge)
![Llama](https://img.shields.io/badge/Llama-3.3--70B-blue?style=for-the-badge)
![Google Sheets](https://img.shields.io/badge/Google%20Sheets-Database-34A853?style=for-the-badge&logo=googlesheets&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

</p>

---

### 🚀 Built with n8n • Groq AI • Llama 3.3 • Google Sheets

</div>

---

# 📌 Overview

The **AI Resume Analyzer** is an intelligent workflow built using **n8n** and **Groq's Llama 3.3 model**.

It allows users to upload a resume in PDF format, extracts the text automatically, analyzes the content using AI, calculates an ATS score, identifies technical and soft skills, highlights strengths and weaknesses, suggests improvements, and stores every analysis in Google Sheets.

---

# ✨ Features

- 📄 Upload Resume (PDF)
- 🤖 AI Resume Analysis
- 🎯 ATS Score Calculation
- 💻 Technical Skills Detection
- 🤝 Soft Skills Detection
- ❌ Missing Skills Identification
- ✅ Strengths & Weaknesses Analysis
- 🚀 Resume Improvement Suggestions
- 💼 Best Matching Job Roles
- 📊 Automatic Google Sheets Logging
- ⚡ Powered by Groq Llama 3.3
- 🔄 Built with n8n (No Coding)

---

# 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| n8n | Workflow Automation |
| Groq API | AI Model |
| Llama 3.3 70B | Resume Analysis |
| Google Sheets | Database |
| PDF Extract | Resume Text Extraction |

---

# 🧩 Workflow

```
User Uploads Resume
        │
        ▼
On Form Submission
        │
        ▼
Extract Text From PDF
        │
        ▼
Groq AI Agent
        │
        ▼
Parse JSON
        │
        ▼
Google Sheets
```

---

# 📸 Screenshots

## 🔹 Workflow

![Workflow](ScreenShot/workflow.png)

---

## 🔹 Resume Upload Form

![Upload Form](ScreenShot/form.png)

---

## 🔹 AI Resume Analysis

![AI Output](ScreenShot/output(2).png)

---



# 📊 Sample Output

```json
{
  "ats_score": 78,
  "summary": "Highly motivated Bioinformatics student...",
  "technical_skills": [
    "C++",
    "Java",
    "Data Structures"
  ],
  "soft_skills": [
    "Communication",
    "Problem Solving"
  ],
  "recommendations": [
    "Gain internship experience",
    "Develop more AI projects"
  ]
}
```

---

# 📂 Project Structure

```
AI-Resume-Analyzer-n8n/
│
├── README.md
│
├── workflow/
│   └── ai_resume_analyzer.json
│
├── prompts/
│   └── system_prompt.txt
│
├── screenshots/
│   ├── workflow.png
│   ├── form.png
│   ├── output.png
│   ├── google_sheets.png
│   └── upload_resume.png
│
└── sample_resume/
    └── sample_resume.pdf
```

---

# 📈 Google Sheets Example

| ATS | Skills | Job Roles | Date |
|------|---------|-----------|------|
| 78 | C++, Java | Software Engineer | 2026-07-17 |

---

# 🎯 Learning Outcomes

This project demonstrates:

- AI Workflow Automation
- Prompt Engineering
- PDF Processing
- API Integration
- Google Sheets Automation
- JSON Parsing
- n8n AI Agents
- LLM Integration


---

# 👩‍💻 Author

**Hamna Ahmed**

Bioinformatics Student | AI & Automation Enthusiast

- GitHub: https://github.com/hamnaahmed80


---

# ⭐ Support

If you found this project helpful:

⭐ Star this repository

🍴 Fork this repository

💬 Share your feedback

---

<div align="center">

### Thanks for visiting!

Built with ❤️ using n8n & Groq AI

</div>
