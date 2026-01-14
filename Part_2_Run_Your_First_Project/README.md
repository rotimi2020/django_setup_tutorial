# Django Setup Part 2 | Silent Python Lab

This folder contains **Part 2** of the Silent Python Lab Django tutorial series.

In this part, we cover:

- Running the existing Django project  
- Activating the virtual environment  
- Running the development server  
- Exploring project folders: `config/` and `core/`  

---

## Folder Structure

 How everything connects inside a Django project

---
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

