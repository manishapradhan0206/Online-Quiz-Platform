# 🧠 QuizMaster — Online Quiz Platform

> A full-stack quiz platform built with **Python & Flask** — featuring 150+ questions across 6 categories, user authentication, a live leaderboard, a full admin panel, and dark/light mode toggle.

---

## ✨ Features

| Feature | Details |
|---|---|
| 📚 150+ Questions | 25 questions in each of 6 categories |
| 🔐 User Auth | Register, Login, Logout with hashed passwords |
| 🏆 Leaderboard | Live ranked leaderboard with avg & best scores |
| 🛠️ Admin Panel | Create, Edit, and Delete quizzes & questions |
| 🌗 Dark / Light Mode | Toggle available in the navbar |
| ⏱️ Timed Questions | Configurable timer per question |
| 💾 Persistent Data | All data saved to JSON files |
| 📊 Results Page | Detailed answer review with explanations & grade |

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/YOUR_USERNAME/Online-Quiz-Platform.git
cd Online-Quiz-Platform
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the App
```bash
python app.py
```

### 4. Open in Browser
Visit 👉 [http://127.0.0.1:5000](http://127.0.0.1:5000)

---

## 🔐 Admin Access

| Field | Value |
|---|---|
| URL | [http://127.0.0.1:5000/admin](http://127.0.0.1:5000/admin) |
| Password | `admin123` |

> ⚠️ Change the admin password in `app.py` before deploying publicly.

---

## 🗂️ Project Structure

```
Online-Quiz-Platform/
├── app.py                  # Main Flask application
├── requirements.txt        # Python dependencies
├── data/
│   ├── quizzes.json        # Quiz & question data
│   ├── users.json          # Registered users
│   └── scores.json         # Quiz attempt scores
├── templates/
│   ├── base.html           # Base layout
│   ├── index.html          # Home / quiz listing
│   ├── play_quiz.html      # Quiz play page
│   ├── results.html        # Results & review page
│   ├── leaderboard.html    # Leaderboard page
│   ├── auth/               # Login & Register pages
│   └── admin/              # Admin panel templates
└── static/                 # CSS, JS, assets
```

---

## 🛠️ Tech Stack

- **Backend**: Python, Flask
- **Frontend**: HTML5, CSS3, JavaScript
- **Auth**: Werkzeug password hashing
- **Storage**: JSON flat-file database

---

## 📸 Pages

- **Home** — Browse all available quizzes by category
- **Quiz Intro** — Quiz details before starting
- **Play** — Timed MCQ quiz with live feedback
- **Results** — Score, grade, and full answer review
- **Leaderboard** — Top users ranked by average score
- **Admin Panel** — Full CRUD for quizzes and questions

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
