# 🌐 Socialite

**Socialite** is a minimalist social networking platform built with **Django 5**, inspired by real-world social apps. It allows users to register, create profiles, follow each other, share bookmarks, and like content — all while keeping the code clean, readable, and extensible.

> 🔨 Built as part of the _"Django 5 By Example"_ book project and now extended for learning and real-world practice.

---

## 🚀 Features

- ✅ User registration, login, logout
- ✅ Custom user model with profile support
- ✅ Follow / unfollow other users
- ✅ Bookmark sharing system
- ✅ Like bookmarks
- ✅ Personalized user feed
- ✅ Full admin control via Django Admin

---

## 🧰 Tech Stack

- **Backend:** Django 5
- **Database:** SQLite (easily switchable to PostgreSQL)
- **Frontend:** HTML, Bootstrap (extendable to Tailwind or HTMX)
- **Python Version:** 3.11+

---

## 📦 Installation

### Clone the repo:

```bash
git clone https://github.com/MahdiHedayati01/socialite.git
cd socialite
```

### Set up a virtual environment:

```bash
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
```

### Install dependencies:

```bash
pip install -r requirements.txt
```

### Run migrations:

```bash
python manage.py migrate
```

### Create superuser (optional):

```bash
python manage.py createsuperuser
```

### Start the development server:

```bash
python manage.py runserver
```

---

## 📁 Project Structure

```
socialite/
├── account/        # User accounts and profiles
├── bookmarks/      # Bookmarking and social features
├── core/           # Home and dashboard
├── templates/      # HTML templates
├── static/         # CSS, JS and static files
├── media/          # User-uploaded files
├── manage.py
└── requirements.txt
```

---

## 🤝 Contributing

Contributions, ideas, and improvements are welcome!  
Feel free to fork the project, open issues, or submit PRs.

---

## 📝 License

This project is licensed under the MIT License.

---

## 🙋‍♂️ Author

**Mahdi Hedayati**  
📫 [@MahdiHedayati01](https://github.com/MahdiHedayati01)

---

> If you found this project useful or interesting, please ⭐ the repository to support the work!
