# News Portal Django Project

## Overview
A responsive and dynamic **news web application** built using **Python (Django)**, **HTML**, **CSS**, **JavaScript**, and **Bootstrap**.  
It allows users to **browse, search, and read news articles** seamlessly with category-wise filtering and an intuitive interface.  
This project also includes an **admin panel** for managing news, categories, and multimedia content.

---

## Features
-  Category-wise news browsing  
- Search functionality for articles  
- Responsive and mobile-friendly UI using Bootstrap  
- Dynamic content rendering with Django Templates  
- Django Admin Panel for content management  
- Video and image news support  

---

## Tech Stack
| Component       | Technology                     |
|----------------|--------------------------------|
| **Backend**    | Python, Django                  |
| **Frontend**   | HTML, CSS, JavaScript, Bootstrap|
| **Database**   | SQLite (default) or MySQL       |
| **Version Control** | Git, GitHub                |

---

## Project Structure
News_portal_Django_Project/
├── mysite/ # Django project configuration
├── news/ # News app containing models, views, etc.
├── static/ # CSS, JS, images
├── templates/ # HTML templates
│ ├── base.html
│ ├── index.html
│ └── news_detail.html
├── manage.py
└── db.sqlite3 # Default database


---

## Setup & Installation

### Clone the repository
```bash
git clone https://github.com/DipankarDubey65/News_portal_Django_Project.git
cd News_portal_Django_Project

## Create and activate a virtual environment
python -m venv venv
venv\Scripts\activate    # On Windows

## Install dependencies
pip install -r requirements.txt

## Install Django
pip install django

# Run migrations
python manage.py migrate

## Start the development server
python manage.py runserver

## Access the app
Open your browser and go to:
http://127.0.0.1:8000/

## Challenges & Learnings
-> Implemented Django's template inheritance for clean and reusable UI.  
-> Designed a responsive layout with Bootstrap.
-> Configured static and media files for proper production handling.
-> Efficiently managed database relationships for categories and news articles.

## Future Enhancements
-> User authentication for personalized feeds.
-> Comment section for articles.
-> Integration with live news APIs.
-> Deployment to cloud hosting (Render/Heroku/AWS).
-> Adding role-based permissions for admin users.

## Why This Project?
This project demonstrates:
-> Backend development with Django and Django ORM.
-> Building scalable, maintainable web applications.
-> Combining frontend responsiveness with backend functionality.
-> Strong understanding of database-driven web apps.
