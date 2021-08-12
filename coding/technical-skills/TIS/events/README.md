Simple booking system for gigs.
Provides alternate dates if provided date unavailable.

Setup Instructions:

Clone the repository
python3 -m venv new_env
source new_env/bin/activate
pip3 install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python poopulation_script.py
python manage.py runserver
