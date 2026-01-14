# Understanding the Django App | Django Setup Part 3

Understanding how Django apps work is a key step for every beginner.

In this video, we cover:

- What a Django app is  
- Registering the app in `settings.py`  
- Exploring important files:
  - `views.py` – where your logic lives
  - `urls.py` – routing URLs
  - `models.py` – database models
  - `admin.py` – Django admin interface
- How everything connects inside a Django project

---

## Folder / App Structure

django_setup_tutorial/
core/
init.py
admin.py
apps.py
models.py
tests.py
views.py
config/
(project files)
manage.py
requirements.txt
README.md


> Note: The `core` app was created in Part 1 using:
> 
> ```bash
> python manage.py startapp core
> ```

---

## Running the Project

Activate your virtual environment if needed:

```bash
# Windows
venv\Scripts\activate

# macOS / Linux
source venv/bin/activate


Run the server:
python manage.py runserver

Open your browser and visit:
http://127.0.0.1:8000/

