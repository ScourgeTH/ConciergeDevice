# Concierge
Home automation solution

# Requirements:
Python 3.6 or higher
Mongodb


# Installation Instructions
1. Clone or copy repo into desired install directory
2. From the Concierge root directory run "pip install -r requirements.txt"
3. IF this is your first install, run "python manage.py makemigrations Concierge"
followed by "python manage.py migrate" to instantiate the Mongodb database
(mongodb must be running for this to work).  Subsequent updates don't require this
step unless the database has been deleted.
5. To access the web app run "python manage.py runserver"
