# mblog
django learning

```python
pip install virtualenv   
virtualenv  VENV
cd VENV
Scripts\activate

django-admin startproject mblog
cd mblog
python manage.py startapp mainsite
cd ..
tree mblog
cd mblog
python manage.py runserver
```

```text
Performing system checks...

System check identified no issues (0 silenced).

You have 13 unapplied migration(s). Your project may not work properly until you apply the migrations for app(s): admin, auth, contenttypes, sessions.
Run 'python manage.py migrate' to apply them.
June 03, 2017 - 19:47:28
Django version 1.11.2, using settings 'mblog.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CTRL-BREAK.
[03/Jun/2017 19:47:39] "GET / HTTP/1.1" 200 1716
Not Found: /favicon.ico
[03/Jun/2017 19:47:39] "GET /favicon.ico HTTP/1.1" 404 1961
```
