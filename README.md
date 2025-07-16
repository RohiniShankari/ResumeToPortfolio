# 🚀 AI Portfolio Generator & Auto-Deployer (Vercel)

This project allows you to **upload a resume PDF and a profile image**, then:

1. 🧠 Uses an **AI agent** to generate a portfolio website (`index.html` and `style.css`)
2. ⚙️ Converts it into a deployable Vite-compatible static site
3. 🌍 Deploys it directly to **Vercel** using its REST API — *no GitHub or CLI required*

---

## 📦 What This Project Does

### ✅ Agent Responsibilities

- Extract structured data from your resume
- Generate a responsive, styled HTML portfolio using your uploaded photo
- Output: `index.html`, `style.css`

### 🔧 Manual Functions (Python)

- Handle file uploads via Google Colab
- Convert output into a Vite-compatible folder
- Package and send files to Vercel via their REST API
- Return the final **public live link** to your portfolio

---

## 🧠 Tech Used

- Python (Google Colab)
- [CrewAI](https://github.com/joaomdmoura/crewai)
- Google Generative AI (Gemini)
- Vercel API (no CLI)
- Vite-compatible static file structure

---

