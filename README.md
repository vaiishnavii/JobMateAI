
# 🚀 JobMateAI - AI-Powered Job Application Assistant

JobMateAI is a **browser extension** that leverages **Generative AI** to **automate and optimize** job applications. It extracts job descriptions, highlights missing skills, generates **ATS-friendly resumes & cover letters**, and even **auto-fills** applications on supported job platforms.

## 🌟 Features
✅ **Extract job descriptions** from LinkedIn, Indeed, and company websites.  
✅ **Analyze and compare** job requirements with your resume.  
✅ **Highlight missing skills** to improve your resume.  
✅ **Generate ATS-optimized resumes & cover letters** instantly.  
✅ **Auto-fill job applications** on supported platforms.  
✅ **One-click apply** for job listings with auto-apply options.  

---

## 🛠️ Tech Stack
### **Frontend (Browser Extension)**
- **React + JavaScript** (Popup UI)
- **Manifest V3** (Chrome Extension API)
- **TailwindCSS** (For styling)

### **Backend (AI Processing)**
- **FastAPI** (Backend server)
- **LangChain** (AI workflow for job matching)
- **Pinecone/FAISS** (Vector search for job relevance)
- **OpenAI GPT-4 / Mistral / LLaMA** (LLMs for resume & cover letter generation)

### **Cloud & Deployment**
- **AWS Lambda / GCP Cloud Run** (For scalable AI processing)
- **Firebase / Supabase** (For authentication & storage)

---

## 📦 Installation
### 1️⃣ Clone the repository
```sh
git clone https://github.com/your-username/apply-genai-extension.git
cd apply-genai-extension
