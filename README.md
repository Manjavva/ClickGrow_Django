# ClickGrow 🌿
<img width="1506" height="1599" alt="clickgrow" src="https://github.com/user-attachments/assets/ea0c567c-db7b-4098-91fc-bebeb17390d6" />

ClickGrow is a web application featuring a Django backend system paired with an interactive frontend client for user authentication, management, and interactive services.

---

## 🛠️ Tech Stack

* **Backend:** Python 3.13, Django framework, SQLite Database
* **Frontend:** HTML5, CSS3, JavaScript (Vanilla JS)
* **Styling:** Custom Modular CSS (`auth.css`, `styles.css`)

---

## 📁 Repository Structure

```text
clickgrow/
├── Backend/
│   ├── accounts/             # Django app for authentication & user management
│   │   ├── migrations/       # Database migration scripts
│   │   ├── forms.py          # User registration and login forms
│   │   ├── models.py         # Custom user database models
│   │   ├── urls.py           # Route configurations for accounts
│   │   └── views.py          # Account processing and logic
│   ├── clickgrown/           # Primary Django project configuration directory
│   │   ├── settings.py       # Global project settings and app definitions
│   │   ├── urls.py           # Main routing entrypoint
│   │   ├── asgi.py / wsgi.py # Web server interface configs
│   ├── static/               # Static assets (CSS stylesheets)
│   ├── templates/            # HTML templates for rendering views
│   ├── db.sqlite3            # SQLite development database
│   ├── manage.py             # Django CLI management script
│   └── requirements.txt      # Python package dependencies
│
└── Frontend/                 # Standalone/integrated frontend client
    ├── index.html            # Main UI entrypoint
    ├── script.js             # Client-side scripts and interactivity
    └── styles.css            # Component styles

```

>made with codex
>by manjavva
