# 🎵🖼️ Image Vibes

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Flask](https://img.shields.io/badge/Flask-Web%20Framework-black)
![AI](https://img.shields.io/badge/AI-Image%20Captioning-purple)
![Database](https://img.shields.io/badge/Database-SQLite-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

**Image Vibes** is an AI-powered web application that generates **creative captions for images** and recommends **music based on the detected mood**.

The application combines **computer vision, natural language processing, and a Flask web application** to create an engaging multimedia experience.

---

# 🚀 Features

* 📤 Upload any image
* 📝 Generate captions using **BLIP Image Captioning Model**
* 😊 Detect mood from generated captions
* 🎶 Recommend music based on mood
* 🔐 Secure login and registration system
* 🔑 Password hashing using **Werkzeug**
* 🗄️ Store users using **SQLite database**

---

# 🧠 Technologies Used

### Frontend

* HTML
* CSS
* Bootstrap

### Backend

* Python
* Flask

### AI / Machine Learning

* HuggingFace Transformers
* BLIP Image Captioning Model

### Database

* SQLite
* SQLAlchemy ORM

---

# ⚙️ Installation

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/Divya18n/Image-Vibes.git
cd Image-Vibes
```

---

## 2️⃣ Create Virtual Environment

```bash
python -m venv venv
```

Activate the environment

Windows

```bash
venv\Scripts\activate
```

Mac / Linux

```bash
source venv/bin/activate
```

---

## 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 4️⃣ Run the Application

```bash
python app.py
```

Open your browser and visit:

```
http://127.0.0.1:7860
```

---

# 📂 Project Structure

```
Image-Vibes
│
├── static/              # CSS and uploaded images
├── templates/           # HTML templates
├── instance/
│     └── users.db       # SQLite database
│
├── utils/               # Caption and mood detection logic
├── app.py               # Main Flask application
├── requirements.txt
├── Dockerfile
├── firebase_config.py
└── README.md
```

---

# 🔄 Application Workflow

1️⃣ User registers or logs in
2️⃣ User uploads an image
3️⃣ BLIP AI model generates a caption
4️⃣ Caption is analyzed to detect mood
5️⃣ Music is recommended based on mood

---

# 👩‍💻 Developer

**Divya**

GitHub
https://github.com/Divya18n

---

# 📜 License

This project is licensed under the **MIT License**.

---

⭐ If you like this project, consider giving it a **star on GitHub**.
