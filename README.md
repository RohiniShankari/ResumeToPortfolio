# ResumeToPortfolio
# 🚀 AI Portfolio Website Generator (CrewAI + Google Colab)

This project is an intelligent agent-based tool that generates a complete personal portfolio website using your uploaded **resume (PDF)** and **profile photo (JPG/PNG)**. 

## 🔧 Features

- 📄 Upload your **resume PDF**
- 🖼️ Upload your **profile picture**
- 🤖 CrewAI agents:
  - **Resume Extractor**: Extracts your professional details from the PDF
  - **Portfolio Website Generator**: Creates a modern HTML/CSS website using the data
- 📦 Outputs:
  - `index.html`
  - `style.css`
  - Your uploaded image
  - ✅ Downloadable as `portfolio.zip`

---

## 📂 How It Works

1. **Resume Upload**: The user uploads a resume in PDF format.
2. **Photo Upload**: The user uploads a JPG or PNG photo.
3. **CrewAI Pipeline**:
   - `Resume Extractor`: Parses structured details from the resume
   - `Website Generator`: Uses those details to generate HTML/CSS
4. **Packaging**: The site files and image are zipped together.
5. **Download**: User can download the `portfolio.zip` instantly.

---

## 🧪 Setup (in Google Colab)

1. Install dependencies (if needed):

```bash
!pip install crewai PyPDF2
