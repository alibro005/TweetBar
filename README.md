# TweetBar

![Python](https://img.shields.io/badge/python-3.10%2B-blue) 
![Django](https://img.shields.io/badge/django-4.2-green) 
![License](https://img.shields.io/badge/license-MIT-yellow) 
![Issues](https://img.shields.io/github/issues/alibro005/TweetBar) 

TweetBar is a Django-based microblogging application that allows users to create, view, edit, and delete short posts (“tweets”) through a clean and intuitive interface. The project demonstrates core Django concepts such as authentication, CRUD functionality, template rendering, and media handling.

This project is intended for **local development and learning purposes** and is **not deployed**.

---

##  Preview Screenshots 
For screenshots of the TweetBar interface [Click here](PREVIEW.md)

##  Installation & Setup Guide
For detailed installation instructions [Click here](INSTALLATION.md)

##  Features

- User authentication (register, login, logout)
- Create, edit, and delete tweets
- Image upload support for tweets
- Timeline displaying tweets from all users
- Responsive UI using Tailwind
- Django Admin panel support
- Simple and modular project structure

---

##  Tech Stack

- Python
- Django
- SQLite (default database)
- HTML / CSS
- Tailwind

---

##  Project Structure

```text
TweetBar/
├── core/
├── settings.py
├── urls.py
├── tweet/
|   ├── templates/
│   └── forms.py
|   └── models.py
|   └── views.py
|   └── urls.py
├── manage.py
├── requirements.txt
├── build.sh
├── Procfile
└── .github/
├── templates/
    ├── home/
    └── layout/
```

##  Usage

- Register a new account or log in
- Create tweets using the tweet bar
- Upload images with tweets
- Edit or delete your own tweets
- View tweets from all users on the timeline
  
---

## Security Notes

- Uses Django’s built-in authentication system
- Configured for development use only
- Not prepared for production deployment

## Project Status

- Not deployed
- Intended for local development and learning
- Can be extended for production use if required

## License

This project is licensed under the [MIT](LICENSE) License.
