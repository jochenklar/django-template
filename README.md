# django-template

An empty django project to get things started. Doesn't even need cookiecutter!

## Setup

```
python3 -m venv env
source env/bin/activate
pip install -r requirements.txt

cp config/settings/sample.local.py config/settings/local.py

./manage.py migrate
./manage.py runserver
```
