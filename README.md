# Resume Keyword Checker (ATS Project)

This project is a simple Python script that simulates an **Applicant Tracking System (ATS)** by scanning resumes for important keywords.  
It helps job seekers ensure their resumes include essential skills, tools, and experiences that recruiters often look for.  

---

## 🚀 Features
- Reads `.docx` resume files.
- Scans for predefined **keywords** such as `Machine Learning`, `Python Flask Framework`, `Hackathon`, `Internship`, etc.
- Prints out which keywords are **FOUND ✅** and which are **MISSING ❌**.
- Gives a final result:  
  - ✅ **Resume Passed** (if all keywords are present)  
  - ❌ **Resume Rejected** (if some keywords are missing)

---

## 🛠️ Technologies Used
- **Python 3**
- **python-docx** (for reading `.docx` files)
- **re** (regular expressions for case-insensitive keyword matching)

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/ats-project.git
cd
