# 🧠 AI Course Companion

A downloadable desktop app that turns **YouTube course videos** into smart, structured learning content:

- ✅ Summarized notes
- 🧭 Mind maps (visualized)
- ❓ Auto-generated quizzes

No hosting needed — fully local using **Tauri + React + Python + GPT-4 API**.

---

## 🔍 Features

- 🎥 Paste any YouTube video link
- 📄 Get full transcript and AI-generated summary
- 🧠 Generate interactive **mind maps**
- ❓ Create quizzes from lectures
- 📦 Works as a **downloadable desktop app**

---

## 🚀 Getting Started (Dev Mode)

### 1. Clone the repo

```bash
git clone https://github.com/YOUR_USERNAME/ai-course-companion.git
cd ai-course-companion

2. Install frontend (React)
    
cd client
npm install
npm run dev


3. Install backend (Python)

cd ../server
pip install -r requirements.txt
uvicorn main:app --reload --port 5000


🧱 Tech Stack
Layer		Tech
Frontend	React + Tailwind CSS
Backend		FastAPI (Python)
AI		    OpenAI GPT-4 API
Transcript	YouTube Transcript API
Packaging	Tauri (Rust-based)

💡 Future Ideas
Multi-video course support

Offline summarization

Export to Notion / PDF

Language translation

📦 Build Desktop App
Coming soon with Tauri!

🤝 Contributions
Open to improvements and feedback!

🪪 License
MIT License