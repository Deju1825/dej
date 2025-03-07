-CLONE REPOSITORY-
git clone [https://github.com/yourusername/django-task-manager.git](https://github.com/Deju1825/dej.git)
cd django-task-manager

-VIRTUAL ENVIRONMENT-
python -m venv dejuenv
dejuenv\Scripts\activate

-REQUIREMENTS-
pip install -r requirements.txt

-DATABASE-
dejdb in NAME

-APPPLY MIGRATIONS-
python manage.py makemigrations
python manage.py migrate

-RUN SERVER-
python manage.py runserver
