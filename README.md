live now: https://resumeanalyzer-ldvryotg4md2v8kurjch3u.streamlit.app/
An intelligent AI-powered Resume Analyzer built using Python and Streamlit that evaluates resumes based on job roles and job descriptions. The tool calculates an ATS (Applicant Tracking System) Match Score, identifies present skills, highlights missing skills, and provides professional improvement suggestions.

🚀 Features

✅ Upload and analyze PDF resumes
✅ Select a target job role
✅ Paste a Job Description (JD) for better matching
✅ Calculates ATS Match Score (%)
✅ Detects skills found in the resume
✅ Shows missing important skills
✅ Generates professional resume improvement suggestions
✅ Simple and interactive Streamlit web interface

🧠 How It Works

The user uploads a PDF resume.

The system extracts text using PyPDF2.

It compares resume content with:

Predefined job role skills

Keywords extracted from job description

The analyzer calculates an ATS match score.

It displays:

Skills found

Missing skills

Suggestions to improve the resume.

🛠️ Tech Stack

Python

Streamlit

PyPDF2

JSON

Natural Text Processing (basic keyword matching)

📂 Project Structure
Resume_Analyzer/
│
├── app2.py              # Main Streamlit application
├── job_roles.json       # Job roles and required skills
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation
⚙️ Installation
1️⃣ Clone the repository
git clone https://github.com/yourusername/resume-analyzer.git
cd resume-analyzer
2️⃣ Install dependencies
pip install -r requirements.txt
3️⃣ Run the application
streamlit run app2.py
📊 Example Output

The analyzer will generate:

📊 ATS Match Score

✅ Skills identified

❌ Missing important skills

💡 Professional resume improvement suggestions
