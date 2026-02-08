# TweetBar Installation Guide

This guide explains how to set up the **TweetBar** Django project for local development.

---

## Prerequisites

Before installing, make sure you have:

- **Python 3.10+** installed  
- **pip** installed (Python package manager)  
- **git** installed (optional, for cloning the repository)

---

## 1. Clone the Repository

Clone the repository to your local machine:

```bash
git clone https://github.com/alibro005/TweetBar.git
cd TweetBar
```
## 2. Create and Activate Virtual Environment

It is recommended to use a virtual environment to manage dependencies:

```bash
# Create a virtual environment
python -m venv venv

# Activate the virtual environment
# Linux/macOS
source venv/bin/activate

# Windows
venv\Scripts\activate

```
## 3. Install Dependencies

Install all required Python packages:

```bash
pip install -r requirements.txt
```
## 4. Apply Database Migrations

Prepare the SQLite database:

```bash
python manage.py migrate
```
## 5. Create a Superuser (Optional)

To access the Django admin panel:

```bash
python manage.py createsuperuser

```

## 6. Run the Development Server

Start the local development server:

```bash
python manage.py runserver

```
Open your browser and go to:


```bash
http://127.0.0.1:8000/

```
