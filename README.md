# 🎓 College Chatbot Web Application

A professional AI-driven chatbot designed to assist students, faculty, and visitors with real-time college-related queries. It uses a **Hybrid Intelligence** approach: an FAQ knowledge base for precision and **GPT-2** for conversational flexibility.

---

## 🚀 Key Features
* **Interactive UI:** Modern, responsive web interface with glassmorphism design.
* **Hybrid Logic:** FAQ-first matching with a GPT-2 fallback mechanism for unknown queries.
* **Real-time Processing:** Fast asynchronous messaging using Flask and JavaScript.
* **Production Ready:** Optimized for Python 3.12 and ready for Render deployment.

---

## 🛠️ Tech Stack
| Component | Technology |
| :--- | :--- |
| **Backend** | Python 3.12, Flask |
| **AI/ML** | GPT-2 (HuggingFace Transformers), PyTorch |
| **Frontend** | HTML5, CSS3, JavaScript (ES6) |
| **Deployment** | Gunicorn, Render |

---

## 📋 Agile Project Management (Sprint Tracking)
We follow a structured sprint-based development lifecycle to ensure quality and timely delivery.

| Issue ID | Title | Priority | Assignee | Status |
| :--- | :--- | :--- | :--- | :--- |
| **CC-1** | Project Setup | High | DEEPESH SHARMA | ✅ DONE |
| **CC-2** | Design Chat UI | High | MOHD KABIR KHAN | ⏳ TO DO |
| **CC-3** | FAQ Knowledge Base | Medium | VINIT KUMAR | ⏳ TO DO |
| **CC-4** | Flask Chat API | High | KUNAL DIWAKAR | ⏳ TO DO |
| **CC-5** | GPT-2 Integration | High | DEVANSH | ⏳ TO DO |
| **CC-9** | Deployment Setup | High | AACHAL SONI | ⏳ TO DO |

---

## 🧠 System Architecture & Workflow
The chatbot follows a tiered logic to ensure the most accurate information is delivered to the user.



1. **User Input:** Receives text from the web interface.
2. **Intent Matching:** Checks the local `faq.json` for keyword matches.
3. **AI Generation:** If no match is found, GPT-2 generates a contextual response.
4. **Response Delivery:** Asynchronous update to the chat UI.

---

## 🏗️ Project Structure
```text
College-Chatbot/
│
├── app.py              # Main Flask Backend Logic
├── requirements.txt    # Python Dependencies
├── README.md           # Documentation
│
├── templates/
│   └── index.html      # Modern Chat UI Layout
│
├── static/
│   └── style.css       # Custom Styling & Glassmorphism
│
└── data/
    └── faq.json        # Predefined Knowledge Base



    ⚙️ Installation & Setup
1️⃣ Clone the Repository
Bash
git clone [https://github.com/yourusername/College-Chatbot.git](https://github.com/yourusername/College-Chatbot.git)
cd College-Chatbot
2️⃣ Create Virtual Environment
Bash
python -m venv venv

# Windows
venv\Scripts\activate

# Mac/Linux
source venv/bin/activate

3️⃣ Install Dependencies
Bash
pip install flask transformers torch gunicorn flask-cors requests

# Generate requirements file
pip freeze > requirements.txt


4️⃣ Run the Application
Bash
python app.py


Access via browser: http://127.0.0.1:5000


🌐 Deployment on Render
Push your project to a GitHub repository.

Log in to Render and create a New Web Service.

Build Command: pip install -r requirements.txt

Start Command: gunicorn app:app


📊 Future Enhancements
[ ] Database Integration: Moving chat logs to SQLite/PostgreSQL.

[ ] Admin Dashboard: GUI to update FAQs without editing JSON files.

[ ] Voice Support: Voice-to-text integration for better accessibility.

[ ] ERP Integration: Linking with college management systems for student records.

👨‍💻 Author
Deepesh Sharma Entrepreneur, Blogger, and B.Tech CSE Student

📄 License
This project is developed for educational purposes and is open for academic collaboration.

