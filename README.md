# flask-quickstart


## Project layout
```
flask-quickstart/
├── app/
│   ├── __init__.py
│   ├── main/
│   │   ├── forms.py
│   │   ├── __init__.py
│   │   └── views.py
│   ├── models/
│   ├── static/
│   │   ├── css/
│   │   ├── img/
│   │   └── js/
│   └── templates/
│           └── login.html
│           └── register.html
│       ├── common/
│       ├── error/
│       │   ├── 404.html
│       │   └── 500.html
│       └── main/
│           └── create.html
│           └── index.html
│           └── update.html
├── CHANGES
├── config.py
├── instance/
│   └── config.py
├── LICENSE
├── manage.py
├── README.md
├── requirements.txt
├── tests/
│   ├── __init__.py
│   └── test_main.py
└── wsgi.py


This is b'coz it should be set to be ignored in the *.gitignore* file. Infact everything except *example_config.py* is set to be ignored. This is where you will store the deployment/production configuration values. You don't want to accidently push this to Github. Rename the file to *config.py* after you clone the repo.


If available, the values in `flask-quickstart/instance/config.py` will override any config values set in tthe environment form `flask-quickstart/config.py` when environment is set to `production` (it is set to `development` by default).

The **wsgi.py** file uses `production` as the environment. This file is to be used by WSGI servers such as Gunicorn.

You can also test production environment using `manage.py`
```

### The file function


__init__.py Used to store initialization code, or bulk import modules.
404.html，500.html Used to return two different types of errors
login.html， register.html  Play the role of registration and login
index.html    Used to store directory information



