Overview
The Personal Finance Tracker is a web application built using Django, designed to help users manage their personal finances. The application allows users to track their income, expenses, and budget goals. It provides an intuitive interface for adding financial transactions, viewing summary reports, and setting budget targets.



Technologies Used:
Backend: Django (Python)
Frontend: HTML, CSS, JavaScript, Bootstrap
Database: SQLite (default) 
Version Control: Git



Installation:
Prerequisites
Python 3.x
pip (Python package installer)
Virtual environment tools (optional but recommended)

steps:

1. clone the repository:
   git clone https://github.com/Tousiha/Personal_Finance_Tracker.git
   cd personal-finance-tracker
   
2.Create a virtual environment :
  python -m venv env
  source env/bin/activate  # On Windows use `env\Scripts\activate`

3.Install dependencies:
  pip install -r requirements.txt

4.set up the database:
  python manage.py migrate

5.Run the development server:
 python manage.py runserver

Access the application:
Open your web browser and go to http://127.0.0.1:8000

Deployment:

On Heroku
Create a new Heroku application:

heroku create your-app-name

Push the code to Heroku:
git push heroku main

Set environment variables on Heroku:
heroku config:set DJANGO_SECRET_KEY='your_secret_key'

Migrate the database:
heroku run python manage.py migrate

Create a superuser (for the admin interface):
heroku run python manage.py createsuperuser



Contributing:

Contributions are welcome! Please follow these steps to contribute:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes.
Commit your changes (git commit -m 'Add some feature').
Push to the branch (git push origin feature-branch).
Create a new Pull Request.



