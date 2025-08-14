AI Resume Screening & Ranking System

This project is an AI-powered resume screening and ranking system built using Streamlit, scikit-learn, and PyPDF2. The application allows users to upload resumes in PDF format, compares them to a given job description, and ranks them based on cosine similarity using TF-IDF.

🚀 Features
Upload multiple PDF resumes.

Enter a job description to compare.

Uses TF-IDF & Cosine Similarity for ranking.

Displays ranked resumes with similarity scores.

📂 Folder Structure

resume_screening_app/
│── .venv/                    
│── app.py                     
│── requirements.txt            
├── resume_ranking.ipynb   
│── data/                       
│   ├── sample_resume.pdf 
│── README.md               
│── .gitignore                   

🛠️ Installation & Setup

1️⃣ Clone the Repository

git clone https://github.com/AbhishekMule13/AI-Powered-Resume.git


2️⃣ (Optional) Create a Virtual Environment

python -m venv .venv

Activate on Windows: source .venv\Scripts\activate

Activate on Mac/Linux: source .venv/bin/activate

3️⃣ Install Dependencies

pip install -r requirements.txt

4️⃣ Run the Application

streamlit run app.py

The app will open in your default web browser.

📌 How It Works

Upload PDF resumes using the file uploader.

Enter a job description in the provided text area.

The system extracts text from the resumes and converts them into TF-IDF vectors.

The job description is compared against resumes using cosine similarity.

Ranked results are displayed with similarity scores.

📡 Deployment

Deploy on Streamlit Cloud (Free)

Push your project to GitHub.

Go to Streamlit Cloud and log in.

Click New App, select your GitHub repo, and set the file path to app.py.

Click Deploy 🚀

🔧 Requirements

streamlit
PyPDF2
pandas
scikit-learn
numpy

Install using:

pip install -r requirements.txt

🎯 End Users

HR & Recruiters – Automates resume screening for faster hiring.

Hiring Managers – Ranks resumes efficiently for job roles.

Job Portals – Enhances resume-job matching accuracy.

AI Enthusiasts & Students – Learn NLP-based resume analysis.

🔮 Future Scope

✅ AI-Based Scoring – Use ML/Deep Learning for better ranking.✅ Advanced NLP – Integrate BERT/GPT for deeper analysis.✅ Multi-Format Support – Add DOCX, TXT & OCR for images.✅ Skill Matching – Extract skills & experience automatically.✅ API Integration – Connect with job portals & HR systems.

🔚 Conclusion

This AI-powered Resume Screening & Ranking System addresses the challenge of manual resume screening, which is time-consuming and inefficient. By leveraging TF-IDF and Cosine Similarity, the system automates resume ranking, ensuring fast, objective, and accurate candidate shortlisting. With PDF text extraction, real-time ranking, and easy deployment via Streamlit, this project provides an efficient, scalable, and user-friendly solution for recruiters, hiring managers, and job portals. 🚀

Streamlit Cloud deploy site:
ai-powered-resume-screening-and-ranking-system-6925.streamlit.app   


**How to Run the Project (First Time)**

1️⃣ Download the project from GitHub
git clone https://github.com/AbhishekMule13/AI-Powered-Resume.git
Move into the project folder
cd AI-Powered-Resume

2️⃣ (Optional) Create a virtual environment
python -m venv .venv
Activate virtual environment (choose the right command for your OS)
Windows:
.venv\Scripts\activate
Mac/Linux:
source .venv/bin/activate

3️⃣ Install all required Python libraries
pip install -r requirements.txt

4️⃣ Run the Streamlit application
streamlit run app.py

5️⃣ Access in your browser
After running the above command, Streamlit will open automatically.
If it doesn’t, copy the Local URL shown (example: http://localhost:8501) and paste it into your browser.

**Next Time (Quick Start)**

cd AI-Powered-Resume
.venv\Scripts\activate       # Windows

*# source .venv/bin/activate  # Mac/Linux

streamlit run app.py

