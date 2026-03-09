# Resume_SkillMatch

🚀 Resume SkillMatch AI (HireReady)

An AI-powered resume analyzer that compares a resume with a job description and provides match scores, missing skills, ATS optimization tips, and AI-generated cover letters.

The application uses the Groq API with Llama 3 to perform deep analysis of resumes and job descriptions.

---

📌 Features
📄 Resume Parsing

Extracts text from PDF and DOCX resumes.
Automatically processes uploaded files.

---

🧠 Job Description Analysis

Identifies:
  Technical skills
  Soft skills
  Experience requirements
  Education qualifications

---

📊 Resume Match Scoring

Calculates resume vs job match percentage
Shows:
  Matching skills
  Missing skills
  Visualized using Plotly charts.

---

⚡ ATS Optimization Suggestions

  Provides actionable recommendations to improve resumes for Applicant Tracking Systems (ATS):
  Keywords to add
  Sections to improve
  Formatting suggestions

---

✉️ AI Cover Letter Generator

  Generates a personalized cover letter based on:
  Resume
  Job description
  Tone options:
  Professional
  Enthusiastic
  Confident
  Friendly

---
⚙️ Installation
1️⃣ Clone the Repository
git clone https://github.com/yourusername/Resume_SkillMatch.git
cd Resume_SkillMatch
2️⃣ Install Dependencies
pip install -r requirements.txt
3️⃣ Setup API Key

Get your free API key from Groq Console.

Add it in the Streamlit sidebar when running the application.

---

4️⃣ Run the Application
streamlit run app.py
📂 Project Structure
Resume_SkillMatch/
│
├── app.py
├── requirements.txt
├── README.md

---

demo-https://resumeskillmatch-ym5b4h9cc7opark8fjvbm6.streamlit.app/
