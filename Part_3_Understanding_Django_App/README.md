# Part 1 — Django Setup in VS Code (Silent Python Lab)

This folder contains **Part 1** of the Silent Python Lab Django tutorial series.

In this tutorial, you will:

- Create a project folder
- Set up a virtual environment
- Install Django
- Create a Django project
- Run the development server

---

## Folder Structure

- `config/` — Django project folder  
- `manage.py` — Django management script  
- `requirements.txt` — Project dependencies  
- `README.md` — Instructions for this part  

---

## Step 1 — Create Project Folder

mkdir Part_1_Django_Setup
cd Part_1_Django_Setup

---

## Step 2 — Create Virtual Environment

python -m venv venv

---

## Step 3 — Activate Virtual Environment

# Windows
venv\Scripts\activate

# macOS / Linux
source venv/bin/activate

---

## Step 4 — Install Django

pip install django

Optional: Save dependencies for future use

pip freeze > requirements.txt

---

## Step 5 — Create Django Project

django-admin startproject config .

---


## Step 6 — Create Django App

django-admin startproject core

---

## Step 7 — Run Development Server

python manage.py runserver

Open your browser and go to:

http://127.0.0.1:8000/

You should see the Django success page.

---

Notes :

Do NOT upload venv/ — it is ignored via .gitignore

Use requirements.txt to reinstall dependencies:

pip install -r requirements.txt



