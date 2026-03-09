---
title: Image Vibes
emoji: 🎵🖼️
colorFrom: purple
colorTo: pink
sdk: docker
app_file: app.py
pinned: false
---

# 🎵🖼️ Image Vibes

**Image Vibes** is an AI-powered web app that generates creative captions for images and recommends music based on the mood detected in faces. It combines advanced computer vision and emotion recognition models with music APIs to create an engaging multimedia experience.

---

## 🚀 Features

- 📤 Upload any image
- 📝 Generate smart captions using **BLIP-2**
- 😊 Detect emotion using **Keywords in generated caption**
- 🎶 Recommend music using **Last.fm API**
- 🔐 Environment variables for API security
- 🧪 Includes test scripts for key modules

---

## 🧠 Technologies Used

- **Frontend:** HTML, CSS, Bootstrap
- **Backend:** Python (Flask)
- **AI Models:** 
  - [BLIP-2](https://huggingface.co/Salesforce/blip2) (image captioning)
- **Music API:** [Last.fm API](https://www.last.fm/api)
- **Database:** SQLite


---

## ⚙️ Getting Started

### 1️⃣ Clone the Repo

```bash
git clone https://github.com/Harshitha-Somu/image-vibes.git
cd image-vibes
```

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
# Activate the virtual environment
# Windows:
venv\Scripts\activate
# macOS/Linux:
source venv/bin/activate
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Add `.env` File

Create a `.env` file in the root directory and add:

```
OPENAI_API_KEY=your_openai_key
LASTFM_API_KEY=your_lastfm_key
```

> ⚠️ Make sure `.env` is listed in `.gitignore`

### 5️⃣ Run the App

```bash
python app.py
```

Open your browser and go to: [http://127.0.0.1:5000](http://127.0.0.1:5000)

---

## 📂 Project Structure

```
image-vibes/
├── static/               # CSS, images, etc.
├── templates/            # HTML files
├── utils/                # Caption & mood detection logic
├── app.py                # Main Flask app
├── firebase_config.py    # Firebase integration
├── requirements.txt      # Dependencies
├── your_database.db      # SQLite database
├── .env                  # API keys (ignored in Git)
└── .gitignore            # Git ignored files
```

---

## 🧪 Tests

Run test scripts to verify image captioning and face detection:

```bash
python test_caption_imports.py
python test_deepface.py
```

---

## 🌐 Visit Site
 
🟢 **Live Demo:** [Open App](https://huggingface.co/spaces/Harshitha-Somu/image-vibes)

---

## 👩‍💻 Developed By

**Harshitha Somu**  
🔗 [GitHub](https://github.com/Harshitha-Somu) • 💼 [LinkedIn](https://www.linkedin.com/in/harshitha-somu-2a2843317?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)

---

## 📃 License

This project is open-sourced under the [MIT License](LICENSE).
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
