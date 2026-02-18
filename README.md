College Chatbot Web Application

A web-based AI chatbot designed to assist students, faculty, and visitors with college-related queries such as admissions, courses, fees, placements, faculty details, and events.

This project is built using:

Python 3.12

Flask (Backend)

GPT-2 (HuggingFace Transformers)

HTML, CSS, JavaScript (Frontend)

Deployable on Render

🚀 Features

Interactive web-based chat interface

FAQ-based response handling

GPT-2 fallback for dynamic responses

Real-time messaging

Easy deployment on Render

Lightweight and Python 3.12 compatible

🏗️ Project Structure
College-Chatbot/
│
├── app.py
├── requirements.txt
├── README.md
│
├── templates/
│   └── index.html
│
├── static/
│   └── style.css
│
└── data/
    └── faq.json

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/yourusername/College-Chatbot.git
cd College-Chatbot

2️⃣ Create Virtual Environment
python -m venv venv
venv\Scripts\activate

3️⃣ Install Dependencies
pip install -r requirements.txt


If requirements.txt is not created yet:

pip install flask transformers torch gunicorn


Then generate:

pip freeze > requirements.txt

4️⃣ Run the Application
python app.py


Open browser:

http://127.0.0.1:5000

🧠 How It Works

User sends a message from the web interface.

Flask receives the request.

System checks FAQ knowledge base.

If match found → predefined response.

If no match → GPT-2 generates response.

Response is returned to user.

🌐 Deployment on Render

Push project to GitHub.

Go to https://render.com

Create New Web Service.

Connect your GitHub repository.

Configure:

Build Command:

pip install -r requirements.txt


Start Command:

gunicorn app:app


Deploy.

📦 Requirements

Python 3.12+

Flask

Transformers

Torch

Gunicorn (for deployment)

📊 Future Enhancements

Admin dashboard

Chat history storage (Database)

Multilingual support

Voice-based chatbot

Integration with college ERP

Authentication system

📄 License

This project is developed for educational purposes.

👨‍💻 Author

Deepesh Sharma
